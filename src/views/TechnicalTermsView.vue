<template>
  <TechnicalTerms title="Les mots et abbréviations à connaître">
  </TechnicalTerms>
  <SwiperComponent :slides="technicalSlides"></SwiperComponent>
</template>
  
  <script>
  // @ is an alias to /src
  import SwiperComponent from "@/components/SwiperComponent.vue";
  import TechnicalTerms from "@/components/TechnicalTerms.vue";
  
  export default {
    name: "TechnicalTermsView",
    components: {
        TechnicalTerms,
        SwiperComponent,
    },
    data() {
        return {
            technicalSlides: [
                { title: "A.T.C", description: "Contrôle du Traffic Aérien | Air Traffic Control", details: "Structure au sol permettant de gérer toute une partie du ciel, qui est lui-même découpé en quartiers. Celle-ci utilise des radars ainsi que des communications radios. Elle forme par l'intermédiaire des contrôleurs aériens, une source d'information précieuse aux pilotes concernant les conditions météorologiques et les approches d'atterrissage. Le cas échéant, elle peut préconiser des déroutes et guider les pilotes en cas d'incident en vol" },
                { title: "A.P.U", description: "Unité d'Alimentation Auxiliaire | Auxiliary Power Unit", details: "Permet à un avion de produire sa propre énergie pour alimenter ses systèmes. D'ordinaire, le moteur à réaction est situé dans la queue de l'avion. Il peut servir au démarrage de l'avion ainsi qu'à sa pressurisation."  },
                { title: "B.E.A", description: "Bureau d'Enquêtes et d'Analyses", details: "Le Bureau d'Enquêtes et d'Analyse pour la sécurité de l'aviation civile est une entité française, fondée en 1946, en charge des incidents graves (sur son sol ou dans les eaux internationnales si l'aéronef est de conception Française) impliquant les aéronefs civils. Toutefois, son rôle n'est pas de déterminer un responsable, mais de mener une investigation scientifique pour déterminer les causes exactes de l'incident. Elle dépend du ministère chargé des transports."  },
                { title: "C.A.T", description: "Aviation Commerciale | Commercial Air Transport", details: "L'aviation commerciale est un service particulier dédié au transport de passagers, de marchandises ou de courrier contre rémunération ou tout autre avantage."  },
                { title: "C.R.N.A.", description: "Centre en-Route de la Navigation Aérienne (Contrôle les aéronefs IFR)", details: "Structure permettant de focaliser l'attention et la sécurité sur tous les appareils en vol. Ainsi, 'En route' signifie ici 'qui n'est ni en phase de décollage ou d'atterrissage', mais bien déjà présent dans les airs. La surveillance se fait sur un secteur bien défini du ciel. NB: En France, il existe cinq structures de ce genre : 'Brest, Athis-Mons, Aix-en-Provence, Reims et Bordeaux'."  },
                { title: "C.C.S", description: "Centre de Coordination Sauvetage | Rescue Coordination Center", details: "Entité fragmentée en trois parties : 'Maritime, Aéronautique, Conjointes'. Créé en 2015, cet organisme est basé à Lyon. Il reçoit les notifications de détresse, accuse leur réception et les retransmet. Enquête sur les zones probables d'accident. Organise et coordonne les recherches. (Dans le cadre d'incidents aériens, il en a la seule charge). Enfin, il peut mobiliser des moyens interministériels et interarmées."  },
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
        };
    },
};
  </script>
  