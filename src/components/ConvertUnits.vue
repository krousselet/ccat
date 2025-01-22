<template>
    <div>
        <section id="feet-in-meters">
            <div class="title-container container">
                <h3>Conversion de PIEDS en METRES</h3>
            </div>
            <br />
            <ul>
                <li>
                    <math>
                        <mi>Altitude en mètres:</mi>
                        <mo>=</mo>
                        <mfrac>
                            <mi>altitude en pieds</mi>
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
                <transition name="fade">
                    <p v-if="metersAnswer" class="meters-answer answer">{{ metersAnswer }}</p>
                </transition>
            </form>
        </section>

        <section id="meters-in-feet">
            <div class="title-container">
                <h3>Conversion de METRES en PIEDS</h3>
            </div>
            <ul>
                <li>
                    <math>
                        <mi>altitude in feet</mi>
                        <mo>=</mo>
                        <mfrac>
                            <mi>altitude in meters</mi>
                            <mn>3</mn>
                        </mfrac>
                        <mo>*</mo>
                        <mn>10</mn>
                    </math>
                </li>
            </ul>
            <form @submit.prevent="convertMetersToFeet">
                <div class="form-container">
                    <label for="meters">Mètres:</label>
                    <input type="number" v-model="meters" id="meters" />
                </div>
                <button type="submit">CONVERTIR</button>
                <transition name="fade">
                    <p v-if="feetAnswer" class="feet-answer answer">{{ feetAnswer }}</p>
                </transition>
            </form>
        </section>

        <section id="kms-in-Nm">
            <div class="title-container">
                <h3>Conversion de kms en Nautic Miles</h3>
            </div>
            <br />
            <ul>
                <li>
                    <math>
                        <mi>distance in Nm</mi>
                        <mo>=</mo>
                        <mfrac>
                            <mi>distance in kms</mi>
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
                <transition name="fade">
                    <p v-if="mnAnswer" class="mn-answer answer">{{ mnAnswer }}</p>
                </transition>
            </form>
        </section>

        <section id="Nm-in-kms">
            <div class="title-container">
                <h3>Conversion de Nautical Miles en Kilomètres</h3>
            </div>
            <br />
            <ul>
                <li>
                    <math>
                        <mi>distance in kms</mi>
                        <mo>=</mo>
                        <mi>distance in Nm</mi>
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
                <transition name="fade">
                    <p v-if="kmsAnswer" class="kms-answer answer">{{ kmsAnswer }}</p>
                </transition>
            </form>
        </section>
    </div>
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
            feetAnswer: "",
            metersAnswer: "",
            mnAnswer: "",
            kmsAnswer: "",
        };
    },
    methods: {
        convertFeetToMeters() {
            if (this.feet !== null) {
                this.metersAnswer = `${(this.feet / 10) * 3} mètres`;
            }
        },
        convertMetersToFeet() {
            if (this.meters !== null) {
                this.feetAnswer = `${(this.meters / 3) * 10} pieds`;
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
    },
};
</script>

<style scoped>

@media (min-width:320px) and (max-width:550px) {
    #conversions {
        display: flex;
        flex-direction: column;
        width: 310px;
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

@media (min-width:551px) and (max-width:12000px) {
    section {
        display: grid;
        grid-template-columns: 1fr 1fr 1fr;
    }
}
</style>
