<template>
    <main>
        <section v-for="(conversion, index) in conversions" :key="index" :id="conversion.id">
            <div class="title-container">
                <h3>{{ conversion.title }}</h3>
            </div>
            <ul>
                <li>
                    <math v-html="conversion.formula"></math>
                </li>
            </ul>
            <form @submit.prevent="convert(conversion)">
                <div class="form-container">
                    <label :for="conversion.inputId">{{ conversion.label }}</label>
                    <input 
                        type="number" 
                        v-model.number="conversion.value" 
                        :id="conversion.inputId" 
                        :min="0"
                        required 
                    />
                </div>
                <button type="submit">CONVERTIR</button>
                <div class="answer-container">
                    <transition name="fade">
                        <p v-if="conversion.answer" class="answer">{{ conversion.answer }}</p>
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
            conversions: [
                { id: "feet-in-meters", title: "PIEDS en METRES", label: "Pieds:", inputId: "feet", formula: "mètres = pieds * 0.3048", value: null, answer: "", factor: 0.3048, unit: "mètres" },
                { id: "meters-in-feet", title: "METRES en PIEDS", label: "mètres:", inputId: "meters", formula: "pieds = mètres / 0.3048", value: null, answer: "", factor: 1 / 0.3048, unit: "pieds" },
                { id: "kms-in-Nm", title: "Kms en Miles Nautiques", label: "Kms:", inputId: "kms", formula: "Nm = kms / 1.852", value: null, answer: "", factor: 1 / 1.852, unit: "Miles Nautique" },
                { id: "Nm-in-kms", title: "Miles Nautiques en Kilomètres", label: "Mn:", inputId: "mn", formula: "kms = Nm * 1.852", value: null, answer: "", factor: 1.852, unit: "Kilomètres" },
                { id: "kmsh-in-kt", title: "Kms / h en Noeuds", label: "Kms/h:", inputId: "kmsh", formula: "Kt = km/h / 1.852", value: null, answer: "", factor: 1 / 1.852, unit: "Noeuds" },
                { id: "kt-in-kmsh", title: "Noeuds en Kilomètres / h", label: "Kt:", inputId: "kt", formula: "kms / h = kt * 1.852", value: null, answer: "", factor: 1.852, unit: "kms par heure" }
            ]
        };
    },
    methods: {
        convert(conversion) {
            if (conversion.value !== null && conversion.value >= 0) {
                conversion.answer = `${(conversion.value * conversion.factor).toFixed(2)} ${conversion.unit}`;
            } else {
                conversion.answer = "Valeur invalide";
            }
        }
    }
};
</script>

<style scoped lang="scss">

.answer-container {
    display: flex;
    justify-content: center;
    align-items: center;
    font-weight: bold;
    color: #007bff;
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
