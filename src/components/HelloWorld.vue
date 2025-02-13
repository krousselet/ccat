<template>
  <div class="animation-container">
    <div class="plane" :class="{ animatePlane: isAnimated }">
      <img :src="planeImage" alt="logo d'un avion">
    </div>
    <div class="sun" :class="{ animateSun: isAnimated }">
      <img :src="sunImage" alt="logo d'un soleil">
    </div>
  </div>
  <div class="text-container">
    <p>Viser l'excellence</p>
  </div>
</template>

<script>
import planeMobile from '@/assets/images/mobile/plane-mobile.svg'
import planeDesktop from '@/assets/images/desktop/plane-desktop.svg'
import sunMobile from '@/assets/images/mobile/sun-mobile.svg'
import sunDesktop from '@/assets/images/desktop/sun-desktop.svg'

export default {
  name: "HelloWorld",
  data() {
    return {
      isAnimated: false, // Controls when animation starts
      windowWidth: window.innerWidth, // Stores current window width
    };
  },
  computed: {
    planeImage() {
      return this.windowWidth >= 992 ? planeDesktop : planeMobile;
    },
    sunImage() {
      return this.windowWidth >= 992 ? sunDesktop : sunMobile;
    }
  },
  mounted() {
    this.startAnimation();
    window.addEventListener("resize", this.updateWindowWidth);
  },
  beforeUnmount() {
    window.removeEventListener("resize", this.updateWindowWidth);
  },
  methods: {
    startAnimation() {
      setTimeout(() => {
        this.isAnimated = true;
      }, 500); // Small delay before animation starts
    },
    updateWindowWidth() {
      this.windowWidth = window.innerWidth;
    }
  }
};
</script>

<style scoped lang="scss">
.animation-container {
  position: relative;
  display: flex;
  justify-content: center;
  align-items: center;
  overflow: hidden;
  height: 800px;
  width: 100%;
  margin: 0 auto;
  background: linear-gradient(rgb(12, 91, 225), white);
}

.plane, .sun {
  position: absolute;
  z-index: 10;
}

.text-container {
  position: relative;
  display: flex;
  justify-content: center;
  align-items: center;
  margin-top: 250px;
  height: 50px;
  overflow: hidden;

  p {
    font-size: 3rem;
    letter-spacing: 15px;
    position: absolute;
    bottom: -250px;
    animation: moveUp 1.5s 3s ease-in-out forwards;
  }
}

img {
  opacity: 0;
  animation: appear .5s .5s ease-in-out forwards
}

/* Plane Animation */
.animatePlane {
  animation: planeMove 4s ease-in-out forwards;
}

/* Sun Animation */
.animateSun {
  animation: sunMove 4s ease-in-out forwards;
}

@keyframes planeMove {
  from {
    left: -100%;
    top: 50%;
  }
  to {
    left: 30%;
    top: 50%;
  }
}

@keyframes sunMove {
  from {
    left: 100%;
    bottom: -100px;
  }
  to {
    left: 50%;
    bottom: 55%;
  }
}

@keyframes moveUp {
  to {
    bottom: 0;
  }
}

@media (min-width: 320px) and (max-width: 991px) {
  .animation-container {
    max-width: 991px;
    max-height: 400px;
  }

  .text-container {
  margin-top: 50px;

  p {
    font-size: 1rem;
    letter-spacing: 10px;
    position: absolute;
    bottom: -250px;
    animation: moveUp 1.5s 3s ease-in-out forwards;
  }
}
}

@media (min-width: 992px) and (max-width: 2048px) {
  .animation-container {
    max-width: 2048px;
    max-height: 500px;
  }


}

@keyframes appear {
  100% {
    opacity: 1;
  }
}
</style>
