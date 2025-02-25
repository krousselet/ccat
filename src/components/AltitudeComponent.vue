<template>
    <main>
        <div class="sky">
            <div class="layer">
                <div class="layer-left">
                    <div class="altitude align">
                        <div class="text-container">
                            <p>Etage = Cirro</p>
                        </div>
                        <div class="text-container">
                            <p>6 000m - 13 000m <br> 19 500ft - 42 500ft</p>
                        </div>
                    </div>
                </div>
                <div class="layer-middle">
                    <div class="threat align">
                        <div class="text-container">
                            <p>Cirro-cumulus : givrage léger</p>
                        </div>
                        <div class="text-container">
                            <p>Cirro-stratus : givrage léger</p>
                        </div>
                        <div class="text-container">
                            <p>Cirro-stratus : givrage léger</p>
                        </div>
                    </div>
                </div>
                <div class="layer-right">
                    <div class="cloud">
                        <div class="image-container">
                            <img :src="cirroCumulus" alt="image du nuage cirro-cumulus">
                        </div>
                        <div class="image-container">
                            <img :src="cirroStratus" alt="image du nuage cirro-stratus">
                        </div>
                        <div class="image-container">
                            <img :src="cirrus" alt="image du nuage cirrus">
                        </div>
                    </div>
                </div>
            </div>
            <div class="layer">
                <div class="layer-left">
                    <div class="altitude align">
                        <div class="text-container">
                            <p>Etage = Alto</p>
                        </div>
                        <div class="text-container">
                            <p>2 000m - 6 000m <br> 6 500ft - 19 500ft</p>
                        </div>
                    </div>
                </div>
                <div class="layer-middle">
                    <div class="threat align">
                        <div class="text-container">
                            <p>Altocumulus : Givrage modéré / Turbulences sévères</p>
                        </div>
                        <div class="text-container">
                            <p>Nimbostratus : Givrage fort / Turbulences</p>
                        </div>
                        <div class="text-container">
                            <p>Altostratus : Givrage modéré / Turbulences</p>
                        </div>
                    </div>
                </div>
                <div class="layer-right">
                    <div class="cloud align">
                        <div class="image-container">
                            <img :src="altoCumulus" alt="image du nuage alto-cumulus">
                        </div>
                        <div class="image-container">
                            <img :src="nimboStratus" alt="image du nuage nimbo-stratus">
                        </div>
                        <div class="image-container">
                            <img :src="altoStratus" alt="image du nuage alto-stratus">
                        </div>
                    </div>
                </div>
            </div>
            <div class="layer">
                <div class="layer-left">
                    <div class="altitude align">
                        <div class="text-container">
                            <p>Etage = Strato</p>
                        </div>
                        <div class="text-container">
                            <p>0 - 2 000m <br> 0 - 6500ft</p>
                        </div>
                    </div>
                </div>
                <div class="layer-middle">
                    <div class="threat align">
                        <div class="text-container">
                            <p>Strato-cumulus : Givrage modéré</p>
                        </div>
                        <div class="text-container">
                            <p>Stratus : Givrage léger</p>
                        </div>
                    </div>
                </div>
                <div class="layer-right">
                    <div class="cloud align">
                        <div class="image-container">
                            <img :src="stratoCumulus" alt="image du nuage strato-cumulus">
                        </div>
                        <div class="image-container">
                            <img :src="stratus" alt="image du nuage stratus">
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </main>
  </template>
  
  <script>
  import stratoCumulus from '@/assets/images/mobile/strato-cumulus.png';
  import stratus from '@/assets/images/mobile/stratus.png';
  import altoCumulus from '@/assets/images/mobile/altocumulus.png';
  import altoStratus from '@/assets/images/mobile/altostratus.png';
  import nimboStratus from '@/assets/images/mobile/nimbostratus.png'
  import cirroCumulus from '@/assets/images/mobile/cirro-cumulus.png';
  import cirroStratus from '@/assets/images/mobile/cirro-stratus.png';
  import cirrus from '@/assets/images/mobile/cirrus.png';
  export default {
    name: "AltitudeComponent",

    setup() {
        return { stratoCumulus, stratus, altoCumulus, altoStratus, cirroCumulus, nimboStratus, cirroStratus, cirrus };
    }
  };
  </script>
  
  <!-- Add "scoped" attribute to limit CSS to this component only -->
  <style scoped lang="scss">
  p {
    color: white;
  }

//  This class allows all the elements to be aligned in the flex box as long as the different divs have the same amount of elements.
  .align {
    height: 100%;
    display: flex;
    flex-direction: column;
    justify-content: space-around;
  }
main {

    .sky {
        height: 1250px;
        background: linear-gradient(180deg, rgba(2,0,36,1) 0%, rgba(9,9,121,1) 35%, rgba(0,212,255,1) 100%);
        display: flex;
        flex-direction: column;

        .layer {
            width: 100%;
            height: 33%;
            border-bottom: 1px solid red;
            display: grid;
            grid-template-columns: 1fr 1fr 1fr;
            grid-template-rows: 1fr 1fr;
            gap: 50px;

            .layer-left {
                height: 100%;
            }

            .layer-middle {
                height: 100%;
            }

            .layer-right {
                height: 100%;
            }
        }
    }
}
  </style>
  