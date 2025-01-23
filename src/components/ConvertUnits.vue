<template>
    <main>
        <section id="feet-in-meters">
            <div class="title-container container">
                <h3>PIEDS en METRES</h3>
            </div>
            <ul>
                <li>
                    <math>
                        <mi>mètres:</mi>
                        <mo>=</mo>
                        <mfrac>
                            <mi>pieds</mi>
                            <mn>10</mn>
                        </mfrac>
                        <mo>*</mo>
                        <mn>3</mn>
                    </math>
                </li>
            </ul>
            <form @submit.prevent="convertFeetToMeters">
                <div class="form-container">
                    <label for="feet">Pieds:</label>
                    <input type="number" v-model="feet" id="feet" />
                </div>
                <button type="submit">CONVERTIR</button>
                <div class="answer-container">
                    <transition name="fade">
                        <p v-if="metersAnswer" class="meters-answer answer">{{ metersAnswer }}</p>
                    </transition>
                </div>
            </form>
        </section>

        <section id="meters-in-feet">
            <div class="title-container">
                <h3>METRES en PIEDS</h3>
            </div>
            <ul>
                <li>
                    <math>
                        <mi>pieds</mi>
                        <mo>=</mo>
                        <mfrac>
                            <mi>mètres</mi>
                            <mn>3</mn>
                        </mfrac>
                        <mo>*</mo>
                        <mn>10</mn>
                    </math>
                </li>
            </ul>
            <form @submit.prevent="convertMetersToFeet">
                <div class="form-container">
                    <label for="meters">mètres:</label>
                    <input type="number" v-model="meters" id="meters" />
                </div>
                <button type="submit">CONVERTIR</button>
                <div class="answer-container">
                    <transition name="fade">
                        <p v-if="feetAnswer" class="feet-answer answer">{{ feetAnswer }}</p>
                    </transition>
                </div>
            </form>
        </section>

        <section id="kms-in-Nm">
            <div class="title-container">
                <h3>Kms en Miles Nautiques</h3>
            </div>
            
            <ul>
                <li>
                    <math>
                        <mi>Nm</mi>
                        <mo>=</mo>
                        <mfrac>
                            <mi>kms</mi>
                            <mn>1.852</mn>
                        </mfrac>
                    </math>
                </li>
            </ul>
            <form @submit.prevent="convertKmsToNm">
                <div class="form-container">
                    <label for="kms">Kms:</label>
                    <input type="number" v-model="kms" id="kms" />
                </div>
                <button type="submit">CONVERTIR</button>
                    <div class="answer-container">
                    <transition name="fade">
                        <p v-if="mnAnswer" class="mn-answer answer">{{ mnAnswer }}</p>
                    </transition>
                </div>
            </form>
        </section>

        <section id="Nm-in-kms">
            <div class="title-container">
                <h3>Miles Nautiques en Kilomètres</h3>
            </div>
            
            <ul>
                <li>
                    <math>
                        <mi>kms</mi>
                        <mo>=</mo>
                        <mi>Nm</mi>
                        <mo>*</mo>
                        <mn>1.852</mn>
                    </math>
                </li>
            </ul>
            <form @submit.prevent="convertNmToKms">
                <div class="form-container">
                    <label for="mn">Mn:</label>
                    <input type="number" v-model="mn" id="mn" />
                </div>
                <button type="submit">CONVERTIR</button>
                <div class="answer-container">
                <transition name="fade">
                        <p v-if="kmsAnswer" class="kms-answer answer">{{ kmsAnswer }}</p>
                    </transition>
                </div>
            </form>
        </section>

        <section id="kmsh-in-kt">
            <div class="title-container">
                <h3>Kms / h en Noeuds</h3>
            </div>
            
            <ul>
                <li>
                    <math>
                        <mi>Kt</mi>
                        <mo>=</mo>
                        <mfrac>
                            <mi>km/h</mi>
                            <mn>2</mn>
                        </mfrac>
                        <mo>+</mo>
                        <mo>10%</mo>
                    </math>
                </li>
            </ul>
            <form @submit.prevent="convertKmshToKt">
                <div class="form-container">
                    <label for="kmsh">Kms/h:</label>
                    <input type="number" v-model="kmsh" id="kmsh" />
                </div>
                <button type="submit">CONVERTIR</button>
                    <div class="answer-container">
                    <transition name="fade">
                        <p v-if="ktAnswer" class="kt-answer answer">{{ ktAnswer }}</p>
                    </transition>
                </div>
            </form>
        </section>

        <section id="kt-in-kmsh">
            <div class="title-container">
                <h3>Noeuds en Kilomètres / h</h3>
            </div>
            
            <ul>
                <li>
                    <math>
                        <mi>kms / h</mi>
                        <mo>=</mo>
                        <mo>(kt * 2)</mo>
                        <mo>-</mo>
                        <mn>10%</mn>
                    </math>
                </li>
            </ul>
            <form @submit.prevent="convertKtToKmsh">
                <div class="form-container">
                    <label for="kt">Kt:</label>
                    <input type="number" v-model="kt" id="kt" />
                </div>
                <button type="submit">CONVERTIR</button>
                <div class="answer-container">
                <transition name="fade">
                        <p v-if="kmshAnswer" class="kmsh-answer answer">{{ kmshAnswer }}</p>
                    </transition>
                </div>
            </form>
        </section>
    </main>
</template>

<script>
export default {
    name: "ConvertUnits",
    data() {
        return {
            feet: null,
            meters: null,
            mn: null,
            kms: null,
            kt: null,
            kmsh: null,
            feetAnswer: "",
            kmsAnswer: "",
            metersAnswer: "",
            mnAnswer: "",
            kmshAnswer: "",
            ktAnswer: "",
        };
    },
    methods: {
        convertFeetToMeters() {
            if (this.feet !== null) {
                this.metersAnswer = `${(this.feet * 0.3048).toFixed(2)} mètres`;
            }
        },
        convertMetersToFeet() {
            if (this.meters !== null) {
                this.feetAnswer = `${(this.meters / 0.3048).toFixed(2)} pieds`; 
            }
        },
        convertKmsToNm() {
            if (this.kms !== null) {
                this.mnAnswer = `${(this.kms / 1.852).toFixed(2)} Miles Nautique`; 
            }
        },
        convertNmToKms() {
            if (this.mn !== null) {
                this.kmsAnswer = `${(this.mn * 1.852).toFixed(2)} Kilomètres`;
            }
        },
        convertKtToKmsh() {
            if (this.kt !== null) {
                this.kmshAnswer = `${(this.kt * 1.852).toFixed(2)} kms par heure`;
            }
        },

        convertKmshToKt() {
            if (this.kmsh !== null) {
                this.ktAnswer = `${(this.kmsh / 1.852).toFixed(2)} Noeuds`;
            }
        },
    },
};
</script>

<style scoped lang="scss">

.answer-container {
    display: flex;
    justify-content: center;
    align-items: center;
}

@media (min-width:320px) and (max-width:990px) {
    #conversions {
        display: flex;
        flex-direction: column;
        width: 310px;
        justify-content: center;
        align-items: center;
        margin: 0 auto;
    }

    button {
        width: 50%;
        display: flex;
        justify-content: center;
        align-items: center;
        margin: 0 auto;
    }

    form {
        display: flex;
        flex-direction: column;
    }

    form div {
        display: flex;
        justify-content: space-evenly;
        align-items: center;
        margin: 15px auto;
    }

    .answer {
        display: flex;
        justify-content: center;
        align-items: center;
        margin-top: 15px;
    }

    #formulas {
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
    }

    ul,
    li {
        display: flex;
        flex-direction: column;
    }

    li {
        display: flex;
        justify-content: space-between;
        align-items: center;
        width: 100%;
        margin: 0 auto;
    }

    math {
        display: flex;
        justify-content: space-around;
        align-items: center;
        width: 100%;
        margin: 5px auto;
    }

}

@media (min-width:991px) and (max-width:12000px) {

    main {
        width: 100%;
        display: grid;
        grid-template-columns: repeat(1, 1fr);
        grid-template-rows: repeat(1, 1fr);

        section {
            display: grid;
            grid-template-columns: repeat(3, 1fr);
            grid-template-rows: repeat(1, 1fr);
            grid-column-gap: 1fr;
            grid-row-gap: 1fr;
            font-size: 1rem;

            .title-container {
                font-size: .9rem;
            }

            ul {
                font-size: 1.2rem;
            }

            form {
                display: grid;
                grid-template-columns: repeat(4, 1fr);
                grid-template-rows: repeat(1, 1fr);
                width: 100%;
                column-gap: 20px;

                label {
                    width: 100%;
                }

                input {
                    min-width: 100%;
                    text-align: center;
                    inset: none;
                    outline: none;
                    transition: .5s ease;
                }

                input:focus {
                    transition: .3s ease;
                    border-bottom:1px solid red;
                }

                button {
                    width: 100%;
                }
            }
        }
    }
}
</style>
