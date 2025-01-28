<template>
    <swiper-container
    :slides-per-view="7"
    :space-between="spaceBetween"
    :pagination="{
      hideOnClick: true
    }"
    :breakpoints="{
      320: {
        slidesPerView: 1,
      },
      768: {
        slidesPerView: 2,
      },
      992: {
        slidesPerView: 3,
      },
      2048: {
        slidesPerView: 5,
      },
      4080: {
        slidesPerView: 7,
      },
    }"
  >
    <swiper-slide v-for="(item, index) in slides" :key="index">
        <slot :slide="item">
            <div class="title-container">
                <h2>{{ item.title }}</h2>
            </div>
            <div class="title-container">
                <h3>{{ item.description }}</h3>
            </div>
            <div class="text">
                <p>{{ item.details }}</p>
            </div>
        </slot>
    </swiper-slide>
</swiper-container>
</template>

<script>

import { register } from 'swiper/element/bundle';
import 'swiper/swiper-bundle.css';
register();

export default {
  name: "SwiperComponent",
  props: {
  slides: {
    type: Array,
    required: true,
    validator: (value) => value.every((slide) => 'title' in slide && 'description' in slide && 'details' in slide),
    default: () =>[
                { title: "A.T.C", description: "Air Traffic Control", details: "Il s'agit de la structure au sol permettant de gérer toute une partie du ciel, qui est lui-même découpé en quartiers" },
                { title: "A.P.U", description: "Auxiliary Power Unit", details: ""  },
                { title: "B.E.A", description: "Bureau d'Enquêtes et d'Analyses", details: ""  },
                { title: "C.A.T", description: "Commercial Air Transport", details: ""  },
                { title: "C.R.N.A.", description: "Centre en-Route de la Navigation Aérienne (Contrôle les aéronefs IFR)", details: ""  },
                { title: "C.C.S", description: "Centre de Coordination Sauvetage", details: ""  },
                { title: "C.I.V", description: "Centre d'Information de Vol (Informe les aéronefs VFR)", details: ""  },
                { title: "C.C.A", description: "Cabin Crew Attestation", details: ""  },
                { title: "C.R.D", description: "Child Restraint Device", details: ""  },
                { title: "C.R.S", description: "Child Restraint System", details: ""  },
                { title: "C.T.A", description: "Certificat de Transporteur Aérien", details: ""  },
                { title: "D.G.A.C", description: "Direction Générale de l'Aviation Civile", details: ""  },
                { title: "E.A.S.A", description: "European Aviation Safety Agency ( AESA Agence Européenne de la Sécurité Aérienne)", details: ""  },
                { title: "F.I.R", description: "Flight Information Région (RIV)", details: ""  },
                { title: "G.T.A", description: "Gendarmerie des Transports Aériens", details: ""  },
                { title: "G.P.U", description: "Ground Power Unit", details: ""  },
                { title: "I.A.T.A.", description: "International Air Transport Association", details: ""  },
                { title: "I.F.E", description: "In-flight Entertainment | Système de divertissement", details: ""  },
                { title: "L.M.E", description: "Liste Minimale d'Equipements | Minimal Equipment List", details: ""  },
                { title: "M.O.P.S.C", description: "Maximum Operational Passenger Seating Configuration", details: ""  },
                { title: "O.2", description: "Oxygène", details: ""  },
                { title: "O.A.C.I", description: "Organisation de l'Aviation Civile Internationale", details: ""  },
                { title: "P.A.F", description: "Police Aux Frontières", details: ""  },
                { title: "P.A.X", description: "Passager", details: ""  },
                { title: "P.E.Q", description: "Equipage", details: ""  },
                { title: "P.C.B", description: "Personnel Complémentaire de Bord", details: ""  },
                { title: "P.N.C", description: "Personnel Navigant Commercial", details: ""  },
                { title: "P.S", description: "Personnel au Sol", details: ""  },
                { title: "P.S.U", description: "Unité de Service aux Passagers | Passenger Service Unit", details: ""  },
                { title: "R.E.X", description: "Retour d'expérience", details: ""  },
                { title: "R.I.V", description: "Région d'Information de Vol | Flight Information Region", details: ""  },
                { title: "S.A.R", description: "Search and Rescue", details: ""  },
                { title: "S.O.P / O.P.S", description: "Procédures Standarts de travail en équipage de l'exploitant", details: "" },
                { title: "G.T.A.", description: "Gendarmerie des Transports Aériens", details: ""  },
                { title: "T.U.C / U.T.C", description: "Temps Universel Coordonné | Universal Time Coordinated", details: ""  },
            ],
        },
    },
};
</script>

<style scoped lang="scss">

swiper-container::part(pagination) {
}

swiper-container::part(bullet-active) {
    background-color: #931116;
}

.text {
    display: flex;
    justify-content: center;
    align-items: center;

    p {
        text-align: justify;
    }
}

@media (min-width:320px) and (max-width: 991px) {
    .title-container {
    margin: 2vw 25px;
    }

    .text {
    margin: 25vw 25px;
        p {
            line-height: 25px;
        }
    }
}

@media (min-width:992px) and (max-width: 2048px) {
    .title-container {
    margin: 4vw 25px;
    }
    .text {
    margin: 12vw 25px;
        p {
            line-height: 25px;
        }
    }
}

@media (min-width:2049px) {
    .title-container {
    margin: 4vw 25px;
    }
    .text {
    margin: 5vw 25px;
        p {
            text-align: justify;
        }
    }
}
// .title-container {
//     margin: 2vw 25px;
// }



</style>