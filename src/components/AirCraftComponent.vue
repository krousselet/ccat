<template>
    <div class="container">
        <div class="title-container">
            <h2>Les mouvements d'un avion:<br> Lacet(Yaw)<br> Tangage (Pitch)<br> Roulis (Roll)</h2>
        </div>
      <div id="scene-container" class="scene-container"></div>
      <div class="controls">
        <button @click="yaw(10)">Lacet Gauche | Yaw Left</button>
        <button @click="yaw(-10)">Lacet Droite | Yaw Right</button>
        <button @click="pitch(10)">Tangage Haut | Pitch Up</button>
        <button @click="pitch(-10)">Tangage Bas | Pitch Down</button>
        <button @click="roll(10)">Roulis Gauche | Roll Left</button>
        <button @click="roll(-10)">Roulis Droite | Roll Right</button>
      </div>
    </div>
  </template>
  
<script>
import { onMounted, ref } from "vue";
import * as THREE from "three";

export default {
  setup() {
    let scene, camera, renderer, aircraft;
    const yawTarget = ref(0);
    const pitchTarget = ref(0);
    const rollTarget = ref(0);

    onMounted(() => {
      initScene();
      animate();
      window.addEventListener("resize", onWindowResize);
    });

    function initScene() {
      scene = new THREE.Scene();
      camera = new THREE.PerspectiveCamera(75, window.innerWidth / window.innerHeight, 0.1, 1000);
      renderer = new THREE.WebGLRenderer();
      renderer.setSize(window.innerWidth * 0.8, window.innerHeight * 0.6);
      document.getElementById("scene-container").appendChild(renderer.domElement);

      let geometry = new THREE.BoxGeometry(2, 1, 4);
      let material = new THREE.MeshBasicMaterial({ color: 0x0077ff, wireframe: true });
      aircraft = new THREE.Mesh(geometry, material);
      scene.add(aircraft);

      camera.position.z = 10;
    }

    function yaw(angle) {
      yawTarget.value += THREE.MathUtils.degToRad(angle);
    }

    function pitch(angle) {
      pitchTarget.value += THREE.MathUtils.degToRad(angle);
    }

    function roll(angle) {
      rollTarget.value += THREE.MathUtils.degToRad(angle);
    }

    function animate() {
      requestAnimationFrame(animate);

      // Smoothly transition to target rotation
      aircraft.rotation.y += (yawTarget.value - aircraft.rotation.y) * 0.1;
      aircraft.rotation.x += (pitchTarget.value - aircraft.rotation.x) * 0.1;
      aircraft.rotation.z += (rollTarget.value - aircraft.rotation.z) * 0.1;

      renderer.render(scene, camera);
    }

    function onWindowResize() {
      camera.aspect = window.innerWidth / window.innerHeight;
      camera.updateProjectionMatrix();
      renderer.setSize(window.innerWidth * 0.8, window.innerHeight * 0.6);
    }

    return { yaw, pitch, roll };
  },
};
</script>
  
  <style scoped lang="scss">

  @media (min-width:320px) and (max-width:991px) {
    .scene-container {
        height: 125px;
    }
        .controls {
            display: grid;
            grid-template-columns: 1fr 1fr;
            grid-template-rows: 1fr 1fr 1fr;
    }
    }
  .controls {
    margin-top: 20px;
  
    button {
        margin: 5px;
        padding: 10px;
        font-size: 16px;
    }
}
    button:nth-child(1) {
        opacity: 0;
        animation: appear .5s .9s ease-in-out forwards
    }
    button:nth-child(2) {
        opacity: 0;
        animation: appear .5s 1.1s ease-in-out forwards
    }
    button:nth-child(3) {
        opacity: 0;
        animation: appear .5s 1.3s ease-in-out forwards
    }
    button:nth-child(4) {
        opacity: 0;
        animation: appear .5s 1.5s ease-in-out forwards
    }
    button:nth-child(5) {
        opacity: 0;
        animation: appear .5s 1.7s ease-in-out forwards
    }
    button:nth-child(6) {
        opacity: 0;
        animation: appear .5s .9s ease-in-out forwards
    }

  .container {
    display: grid;
    grid-template-columns: 1fr;
    grid-template-rows: 1fr;
    width: 99%;
    height: 100%;
    margin: 0 5px;
  }

  .scene-container {
    opacity: 0;
    display: flex;
    justify-content: center;
    align-items: center;
    width: 99%;
    height: 100%;
    margin: 0 5px;
    animation: appear .5s .5s ease-in-out forwards;
  }
  </style>
  