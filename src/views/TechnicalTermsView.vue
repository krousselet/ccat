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
                { title: "C.T.A | A.T.C", description: "Contrôle du Traffic Aérien | Air Traffic Control", details: "Structure au sol permettant de gérer toute une partie du ciel, qui est lui-même découpé en quartiers. Celle-ci utilise des radars ainsi que des communications radios. Elle forme par l'intermédiaire des contrôleurs aériens, une source d'information précieuse aux pilotes concernant les conditions météorologiques et les approches d'atterrissage. Le cas échéant, elle peut préconiser des déroutes et guider les pilotes en cas d'incident en vol" },
                { title: "U.A.A | A.P.U", description: "Unité d'Alimentation Auxiliaire | Auxiliary Power Unit", details: "Permet à un avion de produire sa propre énergie pour alimenter ses systèmes. D'ordinaire, le moteur à réaction est situé dans la queue de l'avion. Il peut servir au démarrage de l'avion ainsi qu'à sa pressurisation."  },
                { title: "B.E.A", description: "Bureau d'Enquêtes et d'Analyses", details: "Le Bureau d'Enquêtes et d'Analyse pour la sécurité de l'aviation civile est une entité française, fondée en 1946, en charge des incidents graves (sur son sol ou dans les eaux internationnales si l'aéronef est de conception Française) impliquant les aéronefs civils. Toutefois, son rôle n'est pas de déterminer un responsable, mais de mener une investigation scientifique pour déterminer les causes exactes de l'incident. Elle dépend du ministère chargé des transports."  },
                { title: "A.C | C.A.T", description: "Aviation Commerciale | Commercial Air Transport", details: "L'aviation commerciale est un service particulier dédié au transport de passagers, de marchandises ou de courrier contre rémunération ou tout autre avantage."  },
                { title: "C.R.N.A.", description: "Centre en-Route de la Navigation Aérienne (Contrôle les aéronefs IFR)", details: "Structure permettant de focaliser l'attention et la sécurité sur tous les appareils en vol. Ainsi, 'En route' signifie ici 'qui n'est ni en phase de décollage ou d'atterrissage', mais bien déjà présent dans les airs. La surveillance se fait sur un secteur bien défini du ciel. NB: En France, il existe cinq structures de ce genre : 'Brest, Athis-Mons, Aix-en-Provence, Reims et Bordeaux'."  },
                { title: "C.C.S", description: "Centre de Coordination Sauvetage | Rescue Coordination Center", details: "Entité fragmentée en trois parties : 'Maritime, Aéronautique, Conjointes'. Créé en 2015, cet organisme est basé à Lyon. Il reçoit les notifications de détresse, accuse leur réception et les retransmet. Enquête sur les zones probables d'accident. Organise et coordonne les recherches. (Dans le cadre d'incidents aériens, il en a la seule charge). Enfin, il peut mobiliser des moyens interministériels et interarmées."  },
                { title: "C.I.V | F.I.C", description: "Centre d'Information de Vol | Flight Information Center (Informe les aéronefs en vol à vue | Visual Flight Rules)", details: "Le centre d'information de vol peut, à la demande du pilote, délivrer des informations nécessaires au bon déroulement du vol (Informations météo, messages compagnies). Etant donné que le vol à vue obéit à certaines règles strictes, c'est une manière de voler particulièrement dangereuse. Il se focalise sur un espace aérien peu ou non contrôlé."  },
                { title: "C.C.A", description: "Cabin Crew Attestation", details: "Nécessaire à tous les individus dont la vocation est de servir et protéger dans les cieux, il s'agit d'une license européenne sous l'égide du règlement 290/2012. En effet, elle est nécessaire pour obtenir un emploi comme hôtesse de l'air ou steward au sein d'une compagnie de l'union européenne."  },
                { title: "C.R.D", description: "Child Restraint Device", details: "AmSafe's Child Aviation Restraint System (CARES) est un système de sécurité pour les enfants mesurant au moins un mètre, et pesant entre 10 et 20 kilos. Il permet de sécuriser l'assise en condition de mouvement sur la piste, de décollage, de turbulence, ou n'importe quelle situation dans laquelle le pilote impose son utilisation."  },
                { title: "C.R.S", description: "Child Restraint System", details: ""  },
                { title: "C.T.A", description: "Certificat de Transporteur Aérien", details: "Le certificat de transporteur aérien est un agrément attestant la capacité de la compagnie aérienne à réaliser des opérations de transport commercial en toute sécurité. L'agrément est délivré par l'autorité de surveillance du transport aérien."  },
                { title: "D.G.A.C", description: "Direction Générale de l'Aviation Civile", details: "La Direction Générale de l'Aviation Civile engloble une série de principes dont notament : 'sécurité, sûreté, développement durable, régulation économique...'. En d'autres mots, elle s'assure du plus haut niveau de sécutité et de sûreté du transport aérien, aussi bien au sol qu'en vol. Elle a également à coeur de réduire les nuisances (sonores et atmosphériques), l'impact écologique et tout ce qui gravite autour de ces notions."  },
                { title: "A.E.S.A | E.A.S.A", description: "European Aviation Safety Agency | Agence Européenne de la Sécurité Aérienne", details: "Cette agence européenne de la sécurité aérienne joue un rôle davantage législatif en s'assurant de l'homogénéité des réglementations et certifications. Elle élabore les règles techniques de l'aéronautique et certifie certains types d'aéronefs et de composants. Par ailleurs, elle a le droit d'agréer ou non les entreprises chargées de la conception, la fabrication et l'entretien des produits aéronautiques. Elle a également le rôle de surveillance, de soutien et de l'assurance de la sécurité au sein des pays de l'Union Européenne."  },
                { title: "R.I.V | F.I.R", description: "Région Information en Vol | Flight Information Région", details: "Il s'agit d'une portion du ciel bien définie au sein d'un pays. En France, il en existe cinq : 'FIR Paris, Fir Reims, FIR Brest (~40% du traffic total), FIR Bordeaux et enfin FIR Marseille.' Deux services sont exclusifs à chacune de ces régions de vol. En premier lieur celui de navigation aérienne (Contrôle et information en vol). En second lieu, les organismes de recherches et de sauvetage."  },
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
  