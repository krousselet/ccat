<template>
  <div class="title-container">
    <h2>Coeur</h2>
  </div>
  <div class="wrapper">
    <div class="heart-container part-container">
      <svg xmlns="http://www.w3.org/2000/svg" width="187" height="269" viewBox="0 0 187 269" fill="none">
        <path
          d="M130.705 129.8C130.471 128.886 130.957 128.432 132.794 127.711C134.56 128.154 135.102 128.701 134.883 130.497C135.191 131.758 134.473 132.086 132.794 131.889C131.209 132.221 130.669 131.902 130.705 129.8Z"
          fill="#656464" stroke="black" stroke-width="1.3926" />
        <path
          d="M46.4523 166.704C44.8283 159.255 44.6512 155.718 50.6301 154.867C53.8079 153.453 56.0495 153.291 60.3781 153.474C63.2636 155.436 64.9403 155.743 68.0374 154.867C69.1047 152.402 70.2063 151.687 72.9115 151.386C75.9078 155.863 77.9768 158.083 83.356 160.809C89.5044 164.107 93.0517 166.417 98.6746 172.275C102.659 178.766 105.62 181.359 112.601 183.415L129.312 198.734C130.493 201.327 129.952 201.76 128.615 202.215L93.1042 200.823C80.0088 198.557 75.4506 196.566 69.43 192.467C53.0357 177.946 48.8926 172.84 46.4523 166.704Z"
          fill="url(#paint0_linear_51_3)" stroke="black" />
        <circle cx="65" cy="165" r="5" fill="yellow" stroke="black" stroke-width="1" @click="
          showInfo(
            'heart',
            'Ventricule droit',
            'Le ventricule droit se contracte et envoie le sang par la valvule pulmonaire dans l\'artère pulmonaire, puis dans les poumons. Simultanément, le sang riche en oxygène provenant des poumons est amené au cœur par les veines pulmonaires.'
          )
          " />
        <path
          d="M109.815 110.304C104.952 110.506 103.729 111.549 102.156 113.785C102.344 121.972 101.615 126.423 97.9782 133.978C96.9966 140.152 97.0507 143.52 98.6745 149.297L120.26 172.274C120.239 168.056 120.65 166.613 121.652 164.615C120.777 156.121 121.446 154.073 123.045 151.386C128.631 142.382 127.568 138.174 126.526 130.497C123.731 113.924 118.897 112.235 109.815 110.304Z"
          fill="url(#paint1_linear_51_3)" stroke="black" stroke-width="1.3926" />
        <circle cx="113" cy="125" r="5" fill="yellow" stroke="black" stroke-width="1" @click="
          showInfo(
            'heart',
            'Ventricule gauche',
            'Le ventricule gauche se contracte et propulse le sang dans l\'aorte. La valve située au départ de l\'aorte se ferme. Le sang est distribué dans tout l\'organisme. Les artères coronaires, alimentées par l\'aorte, assurent l\'approvisionnement en sang oxygéné du cœur lui-même.'
          )
          " />
        <path
          d="M145.326 108.215C135.375 105.784 130.143 106.139 120.956 107.519C125.745 114.126 128.422 117.838 130.007 127.015H136.274C135.448 119.721 136.842 115.611 145.326 108.215Z"
          fill="url(#paint2_linear_51_3)" stroke="black" stroke-width="1.3926" @click="
            showInfo(
              'heart',
              'Valve aortique',
              'La valve aortique contrôle le passage du sang entre le ventricule gauche et l\'aorte.'
            )
            " />
        <circle cx="110" cy="109" r="5" fill="yellow" stroke="black" stroke-width="1" @click="
          showInfo(
            'heart',
            'Valve aortique',
            'La valve aortique contrôle le passage du sang entre le ventricule gauche et l\'aorte.'
          )
          " />
        <path
          d="M145.326 108.215C135.375 105.784 130.143 106.139 120.956 107.519C125.745 114.126 128.422 117.838 130.007 127.015H136.274C135.448 119.721 136.842 115.611 145.326 108.215Z"
          fill="url(#paint2_linear_51_3)" stroke="black" stroke-width="1.3926" />
        <path
          d="M109.12 106.823C107.314 107.098 106.614 107.723 107.031 109.608C107.4 110.271 108.369 110.449 111.904 110.304V108.215C111.508 107.187 110.903 106.879 109.12 106.823Z"
          fill="#470D0B" stroke="black" stroke-width="1.3926" @click="
            showInfo(
              'heart',
              'Valve Aortique',
              'Contrôle le passage du sang entre le ventricule gauche et l\'aorte.'
            )
            " />
        <path
          d="M77.0886 106.126L75.696 111C71.734 97.0102 68.2225 93.0109 59.6811 92.2002C51.244 92.6358 46.9595 94.8891 41.5774 108.911C36.8932 122.005 37.127 129.13 40.1848 141.637L45.7552 144.423C55.2017 146.252 57.6202 147.754 60.3774 150.689V153.474H55.5033C43.0512 154.719 42.9185 159.044 47.844 169.489C55.8937 182.131 61.9932 187.426 74.3034 195.252C86.9262 200.729 96.7953 201.799 117.474 201.519C128.821 203.401 131.745 203.003 130.007 199.43L111.904 182.023C91.7788 159.494 89.3519 154.845 89.622 150.689C91.7943 138.001 94.6595 130.667 102.155 117.267C97.1693 131.664 95.7694 139.011 98.6739 149.297L131.4 184.112C146.673 196.69 148.07 189.167 151.593 177.845V155.563C154.558 138.654 152.602 129.421 145.326 115.178C139.302 122.278 137.887 127.024 136.97 127.015C134.985 119.514 136.6 115.536 145.326 108.911C148.058 104.265 148.177 101.914 148.111 97.7706C145.054 89.1114 141.951 86.257 136.97 80.3631C142.434 82.0068 145.61 83.4122 152.289 90.1113C153.883 96.7898 154.456 101.842 154.378 115.178C161.9 125.526 166.01 131.892 169 166.008C168.565 185.585 170.148 198.334 158.556 207.089C150.732 211.501 149.442 217.859 138.763 218.927C125.77 215.921 95.9934 214.052 80.9706 211.964C65.9478 209.875 51.8279 197.762 45.7552 188.986C30.6619 174.654 28.2779 156.168 26.2588 119.356C30.9337 116.521 31.9832 114.821 32.5255 111.697L39.4885 99.1632C41.1402 96.4959 41.1299 94.9658 40.1848 92.2002C49.5965 83.4122 56.023 82.359 68.733 87.3261L76.3923 100.556L77.0886 106.126Z"
          fill="#E3C398" stroke="black" stroke-width="1.3926" />
        <path
          d="M61.0739 151.386C57.9277 146.756 54.1838 145.638 46.4517 144.423C49.9246 133.42 55.2384 129.811 74.9999 131.193C69.2813 140.652 69.7017 143.967 71.5184 149.297C64.3487 147.857 62.8892 148.918 61.0739 151.386Z"
          fill="url(#paint3_linear_51_3)" stroke="black" stroke-width="1.3926" />
        <path
          d="M67.3426 152.778H63.1648C62.5655 150.566 63.3113 150.048 65.95 149.993C67.2089 150.76 67.5216 151.358 67.3426 152.778Z"
          fill="#656464" stroke="black" stroke-width="1.3926" @click="
            showInfo(
              'heart',
              'Valve Tricuspide',
              'La valve tricuspide (valve atrio-ventriculaire) correspond à la valve du cœur qui crée une séparation entre le ventricule droit et l\'oreillette droite. Elle a pour rôle d\'empêcher que le sang ne reflue entre l\'oreillette droite et le ventricule droit.'
            )
            " />
        <circle cx="65" cy="150" r="5" fill="yellow" stroke="black" stroke-width="1" @click="
          showInfo(
            'heart',
            'Valve Tricuspide',
            'La valve tricuspide (valve atrio-ventriculaire) correspond à la valve du cœur qui crée une séparation entre le ventricule droit et l\'oreillette droite. Elle a pour rôle d\'empêcher que le sang ne reflue entre l\'oreillette droite et le ventricule droit.'
          )
          " />
        @click="showInfo('heart','Veine Cave Supérieure', 'La veine cave
        supérieure est une veine large et courte qui transporte la majeure
        partie du sang désoxygéné de la partie du corps située au-dessus du
        diaphragme vers l\'atrium droit (anciennement oreillette droite) du
        cœur.')"
        <path
          d="M39.4903 134.674C41.7349 143.156 40.4354 141.177 45.757 143.726C51.2808 131.906 58.1161 129.658 75.0005 131.193C76.9816 126.783 76.4481 121.2 75.0005 110.304C70.5258 97.6613 67.1499 93.9874 59.6828 92.8965C41.099 93.4479 37.2457 126.193 39.4903 134.674Z"
          fill="url(#paint4_linear_51_3)" stroke="black" stroke-width="1.3926" @click="
            showInfo(
              'heart',
              'Oreillette Droite',
              'Le rôle de l\'oreillette droite du cœur est de recevoir le sang veineux désoxygéné. Elle reçoit le sang provenant des veines caves supérieure et inférieure et l\'envoie au ventricule droit. La valvule tricuspide sépare l\'oreillette droite du ventricule droit et s\'ouvre pour permettre au sang de pénétrer dans le ventricule droit'
            )
            " />
        <circle cx="60" cy="115" r="5" fill="yellow" stroke="black" stroke-width="1" @click="
          showInfo(
            'heart',
            'Oreillette Droite',
            'Le rôle de l\'oreillette droite du cœur est de recevoir le sang veineux désoxygéné. Elle reçoit le sang provenant des veines caves supérieure et inférieure et l\'envoie au ventricule droit. La valvule tricuspide sépare l\'oreillette droite du ventricule droit et s\'ouvre pour permettre au sang de pénétrer dans le ventricule droit'
          )
          " />
        <path
          d="M146.023 107.519C135.532 105.92 129.841 105.759 120.26 107.519L110.512 96.378C108.936 91.0335 111.465 88.373 118.171 83.8446C122.136 81.0778 127.052 80.6488 136.971 80.3631C145.978 90.9879 150.413 96.9424 146.023 107.519Z"
          fill="url(#paint5_linear_51_3)" stroke="black" stroke-width="1.3926" @click="
            showInfo(
              'heart',
              'Oreillette Gauche',
              'L\'oreillette gauche joue un rôle important dans le remplissage ventriculaire gauche. Elle agit comme une “pompe contractile” qui fournit 15 à 30% du remplissage total du ventricule gauche, un “réservoir” qui collecte le retour veineux pulmonaire pendant la systole ventriculaire et un “conduit” permettant le passage du sang de l\’oreillette au ventricule gauche pendant la diastole ventriculaire précoce. Le sang oxygéné qui provient des poumons est conduit dans l\'oreillette gauche par les quatre veines pulmonaires'
            )
            " />
        <circle cx="130" cy="95" r="5" fill="yellow" stroke="black" stroke-width="1" @click="
          showInfo(
            'heart',
            'Oreillette Gauche',
            'L\'oreillette gauche joue un rôle important dans le remplissage ventriculaire gauche. Elle agit comme une “pompe contractile” qui fournit 15 à 30% du remplissage total du ventricule gauche, un “réservoir” qui collecte le retour veineux pulmonaire pendant la systole ventriculaire et un “conduit” permettant le passage du sang de l\’oreillette au ventricule gauche pendant la diastole ventriculaire précoce. Le sang oxygéné qui provient des poumons est conduit dans l\'oreillette gauche par les quatre veines pulmonaires'
          )
          " />
        <path
          d="M77.7853 119.356C75.9952 114.685 75.9528 111.788 77.7853 106.126C88.2258 104.419 92.7637 105.203 97.978 110.304L99.3706 117.963C99.3874 120.475 100.113 122.043 92.4076 122.837C89.0401 122.396 88.3271 120.977 87.5335 117.963C84.9015 119.564 82.6303 119.741 77.7853 119.356Z"
          fill="url(#paint6_linear_51_3)" stroke="black" stroke-width="1.3926" @click="
            showInfo(
              'heart',
              'Valvule Sigmoïde',
              'Une valve sigmoïde est une valve artérielle assurant la liaison entre un ventricule et les vaisseaux partant du cœur.'
            )
            " />
        <circle cx="90" cy="112" r="5" fill="yellow" stroke="black" stroke-width="1" @click="
          showInfo(
            'heart',
            'Valvule Sigmoïde',
            'Une valve sigmoïde est une valve artérielle assurant la liaison entre un ventricule et les vaisseaux partant du cœur.'
          )
          " />
        <path
          d="M24.868 99.1632H38.794C38.1149 102.599 36.9053 104.228 33.9185 106.822H22.7791C20.8344 103.18 21.4095 101.531 24.868 99.1632Z"
          fill="#716173" />
        <path
          d="M33.2222 111.697H23.474C20.6234 114.502 20.8556 116.006 22.0815 118.66H26.9556C30.8972 116.556 31.7145 114.803 33.2222 111.697Z"
          fill="#716173" />
        <path
          d="M24.868 99.1632H38.794C38.1149 102.599 36.9053 104.228 33.9185 106.822H22.7791C20.8344 103.18 21.4095 101.531 24.868 99.1632Z"
          stroke="black" stroke-width="1.3926" @click="
            showInfo(
              'heart',
              'Veines Pulmonaires droite',
              'Les quatre veines pulmonaires (une pour chaque lobe pulmonaire) sont des veines chargées de véhiculer le sang oxygéné jusqu\'aux poumons et jusqu\'au cœur, chargé de le propulser dans le reste de l\'organisme'
            )
            " />
        <circle cx="25" cy="106" r="5" fill="yellow" stroke="black" stroke-width="1" @click="
          showInfo(
            'heart',
            'Veines Pulmonaires droite',
            'Les quatre veines pulmonaires (une pour chaque lobe pulmonaire) sont des veines chargées de véhiculer le sang oxygéné jusqu\'aux poumons et jusqu\'au cœur, chargé de le propulser dans le reste de l\'organisme'
          )
          " />
        <path
          d="M33.2222 111.697H23.474C20.6234 114.502 20.8556 116.006 22.0815 118.66H26.9556C30.8972 116.556 31.7145 114.803 33.2222 111.697Z"
          stroke="black" stroke-width="1.3926" @click="
            showInfo(
              'heart',
              'Veines Pulmonaires droite',
              'Les quatre veines pulmonaires (une pour chaque lobe pulmonaire) sont des veines chargées de véhiculer le sang oxygéné jusqu\'aux poumons et jusqu\'au cœur, chargé de le propulser dans le reste de l\'organisme'
            )
            " />
        <path
          d="M101.46 113.785C95.3308 106.233 90.4448 104.115 77.7861 106.126L77.0898 101.252C89.0789 84.4475 95.3083 75.5564 93.801 73.4001L83.3565 66.4371L86.838 47.637L104.245 53.2074C114.44 55.6442 120.581 55.9695 132.794 54.6L157.164 50.4222L158.557 56.6889C149.546 57.4191 147.799 58.6619 147.416 61.563C148.902 65.5077 151.612 66.3839 158.557 66.4371V73.4001L141.149 71.3112C131.303 73.5525 127.365 75.2469 123.046 78.9705C106.631 92.3248 103.227 99.8503 101.46 113.785Z"
          fill="#CCB7BB" stroke="black" stroke-width="1.3926" @click="
            showInfo(
              'heart',
              'Artère pulmonaire',
              'L\'artère pulmonaire droite est un vaisseau sanguin essentiel dans le corps humain, responsable de transporter le sang oxygéné du ventricule droit du cœur vers les poumons pour y subir un processus de réoxygénation.'
            )
            " />
        <circle cx="107" cy="70" r="5" fill="yellow" stroke="black" stroke-width="1" @click="
          showInfo(
            'heart',
            'Artère pulmonaire',
            'L\'artère pulmonaire droite est un vaisseau sanguin essentiel dans le corps humain, responsable de transporter le sang oxygéné du ventricule droit du cœur vers les poumons pour y subir un processus de réoxygénation.'
          )
          " />
        <path
          d="M162.733 88.7187C159.201 90.0806 156.97 90.0985 152.985 90.1113C153.449 92.4323 154.377 97.2135 154.377 97.7706C157.368 95.4525 159.674 94.516 164.822 93.5928L162.733 88.7187Z"
          fill="#716173" />
        <path
          d="M164.822 102.645C159.4 102.239 157.286 101.541 154.377 99.8595V108.215L165.518 107.519C163.631 105.824 163.884 104.704 164.822 102.645Z"
          fill="#716173" />
        <path
          d="M162.733 88.7187C159.201 90.0806 156.97 90.0985 152.985 90.1113C153.449 92.4323 154.377 97.2135 154.377 97.7706C157.368 95.4525 159.674 94.516 164.822 93.5928L162.733 88.7187Z"
          stroke="black" stroke-width="1.3926" @click="
            showInfo(
              'heart',
              'Veines Pulmonaires gauche',
              'Les quatre veines pulmonaires (une pour chaque lobe pulmonaire) sont des veines chargées de véhiculer le sang oxygéné jusqu\'aux poumons et jusqu\'au cœur, chargé de le propulser dans le reste de l\'organisme'
            )
            " />
        <circle cx="160" cy="96" r="5" fill="yellow" stroke="black" stroke-width="1" @click="
          showInfo(
            'heart',
            'Veines Pulmonaires gauche',
            'Les quatre veines pulmonaires (une pour chaque lobe pulmonaire) sont des veines chargées de véhiculer le sang oxygéné jusqu\'aux poumons et jusqu\'au cœur, chargé de le propulser dans le reste de l\'organisme'
          )
          " />
        <path
          d="M164.822 102.645C159.4 102.239 157.286 101.541 154.377 99.8595V108.215L165.518 107.519C163.631 105.824 163.884 104.704 164.822 102.645Z"
          stroke="black" stroke-width="1.3926" @click="
            showInfo(
              'heart',
              'Veines Pulmonaires gauche',
              'Les quatre veines pulmonaires (une pour chaque lobe pulmonaire) sont des veines chargées de véhiculer le sang oxygéné jusqu\'aux poumons et jusqu\'au cœur, chargé de le propulser dans le reste de l\'organisme'
            )
            " />
        <path
          d="M61.0755 58.0816C58.2903 65.0446 65.0939 84.364 77.0904 100.556L93.8014 76.8817L91.0163 67.1335C90.2221 59.9221 91.4442 57.1429 95.8903 53.9038C101.211 50.7737 104.532 50.9642 111.905 54.6001L124.439 78.2743L136.276 78.9706L132.098 53.9038C129.802 45.3492 128.434 41.9915 125.831 39.9779L108.424 28.1408C105.694 26.5392 105.665 25.8625 105.639 24.6593V17.6963L104.246 17H99.3718L97.9792 17.6963V26.0519H94.4977L91.0163 17.6963L84.0533 19.7852V23.2667L87.5348 30.926L85.4459 33.7112H81.9644L75.0014 24.6593H72.9129L68.0385 28.1408V30.926C71.0429 34.0037 72.757 35.7049 72.9129 41.3705C71.52 46.9408 63.8607 51.1186 61.0755 58.0816Z"
          fill="#D3574E" />
        <path
          d="M98.6755 246.082C99.692 222.133 98.5488 216.926 95.194 214.053L125.831 217.534C120.737 217.484 122.856 231.361 123.046 246.082C121.175 250.36 118.775 251.8 112.602 253.045C104.969 252.183 101.764 250.804 98.6755 246.082Z"
          fill="#D3574E" stroke="black" />
        <circle cx="110" cy="230" r="5" fill="yellow" stroke="black" stroke-width="1" @click="
          showInfo(
            'heart',
            'Aorte',
            'L\'aorte est la plus grande et la principale artère du corps humain, partant du cœur, plus précisément du ventricule gauche. Elle a pour fonction de distribuer le sang oxygéné à l\'ensemble de l\'organisme, sauf à la circulation fonctionnelle des poumons. L\'aorte se divise en plusieurs parties, notamment l\'aorte thoracique et l\'aorte abdominale, et elle est essentielle pour le transport du sang vers les organes et les membres'
          )
          " />
        <path
          d="M61.0755 58.0816C58.2903 65.0446 65.0939 84.364 77.0904 100.556L93.8014 76.8817L91.0163 67.1335C90.2221 59.9221 91.4442 57.1429 95.8903 53.9038C101.211 50.7737 104.532 50.9642 111.905 54.6001L124.439 78.2743L136.276 78.9706L132.098 53.9038C129.802 45.3492 128.434 41.9915 125.831 39.9779L108.424 28.1408C105.694 26.5392 105.665 25.8625 105.639 24.6593V17.6963L104.246 17H99.3718L97.9792 17.6963V26.0519H94.4977L91.0163 17.6963L84.0533 19.7852V23.2667L87.5348 30.926L85.4459 33.7112H81.9644L75.0014 24.6593H72.9129L68.0385 28.1408V30.926C71.0429 34.0037 72.757 35.7049 72.9129 41.3705C71.52 46.9408 63.8607 51.1186 61.0755 58.0816Z"
          stroke="black" stroke-width="1.3926" @click="
            showInfo(
              'heart',
              'Aorte',
              'L\'aorte est la plus grande et la principale artère du corps humain, partant du cœur, plus précisément du ventricule gauche. Elle a pour fonction de distribuer le sang oxygéné à l\'ensemble de l\'organisme, sauf à la circulation fonctionnelle des poumons. L\'aorte se divise en plusieurs parties, notamment l\'aorte thoracique et l\'aorte abdominale, et elle est essentielle pour le transport du sang vers les organes et les membres'
            )
            " />
        <circle cx="80" cy="70" r="5" fill="yellow" stroke="black" stroke-width="1" @click="
          showInfo(
            'heart',
            'Aorte',
            'L\'aorte est la plus grande et la principale artère du corps humain, partant du cœur, plus précisément du ventricule gauche. Elle a pour fonction de distribuer le sang oxygéné à l\'ensemble de l\'organisme, sauf à la circulation fonctionnelle des poumons. L\'aorte se divise en plusieurs parties, notamment l\'aorte thoracique et l\'aorte abdominale, et elle est essentielle pour le transport du sang vers les organes et les membres'
          )
          " />
        <path
          d="M98.6755 246.082C99.692 222.133 98.5488 216.926 95.194 214.053L125.831 217.534C120.737 217.484 122.856 231.361 123.046 246.082C121.175 250.36 118.775 251.8 112.602 253.045C104.969 252.183 101.764 250.804 98.6755 246.082Z"
          stroke="black" stroke-width="1.3926" @click="
            showInfo(
              'heart',
              'Aorte',
              'L\'aorte est la plus grande et la principale artère du corps humain, partant du cœur, plus précisément du ventricule gauche. Elle a pour fonction de distribuer le sang oxygéné à l\'ensemble de l\'organisme, sauf à la circulation fonctionnelle des poumons. L\'aorte se divise en plusieurs parties, notamment l\'aorte thoracique et l\'aorte abdominale, et elle est essentielle pour le transport du sang vers les organes et les membres'
            )
            " />
        <path
          d="M36.7036 46.9407V51.1185C38.1883 56.1049 38.8519 59.3305 39.4888 66.4371L40.8814 91.5038C44.3557 88.8059 46.4954 87.2901 53.4148 84.5408C59.6261 84.498 63.0063 85.029 68.7333 87.326L63.163 78.2742C60.6183 72.5722 60.5806 69.6262 60.3778 64.3482C60.4717 58.4722 61.3091 56.1691 63.163 52.5111V46.9407L56.8963 43.4592H46.4518L36.7036 46.9407Z"
          fill="url(#paint7_linear_51_3)" stroke="black" stroke-width="1.3926" @click="
            showInfo(
              'heart',
              'Veine Cave Supérieure',
              'La veine cave supérieure est une veine large et courte qui transporte la majeure partie du sang désoxygéné de la partie du corps située au-dessus du diaphragme vers l\'atrium droit (anciennement oreillette droite) du cœur.'
            )
            " />
        <circle cx="53" cy="75" r="5" fill="yellow" stroke="black" stroke-width="1" @click="
          showInfo(
            'heart',
            'Veine Cave Supérieure',
            'La veine cave supérieure est une veine large et courte qui transporte la majeure partie du sang désoxygéné de la partie du corps située au-dessus du diaphragme vers l\'atrium droit (anciennement oreillette droite) du cœur.'
          )
          " />
        <path
          d="M35.3107 65.7409L19.9921 65.0446C18.5619 68.0357 18.7812 69.7127 19.9921 72.7039H32.5254C34.9933 75.1508 34.7945 76.5238 32.5254 78.9705H22.0809C20.1131 80.5139 19.7624 81.4546 19.2958 83.1483C19.161 85.2258 19.2274 86.3642 21.3847 88.0224L40.8811 85.2372L39.4885 64.3483L35.3107 65.7409Z"
          fill="#B790A7" stroke="black" stroke-width="1.3926" />
        @click="showInfo('heart','Veine Pulmonaires droite', 'Les veines
        pulmonaires sont les veines qui transportent du sang riche en oxygène
        des poumons vers l\'atrium gauche (anciennement oreillette gauche) du
        cœur. Elles sont au nombre de quatre, soit deux pour chaque poumon. ')"
        <path
          d="M51.3258 233.549L46.4517 191.771C53.4487 200.918 59.202 205.139 73.6073 210.571L74.9999 232.156C73.6086 237.131 71.4804 239.05 64.5554 240.512C56.3255 238.611 53.3484 237.113 51.3258 233.549Z"
          fill="#89B7D3" stroke="black" stroke-width="1.3926" @click="
            showInfo(
              'heart',
              'Veine Cave Inférieure',
              'La veine cave inférieure est une veine large située principalement dans l\'abdomen, issue de la réunion des deux veines iliaques communes et qui s\'ouvre dans l\'atrium droit (anciennement oreillette droite) du cœur.'
            )
            " />
        <circle cx="65" cy="220" r="5" fill="yellow" stroke="black" stroke-width="1" @click="
          showInfo(
            'heart',
            'Veine Cave Inférieure',
            'La veine cave inférieure est une veine large située principalement dans l\'abdomen, issue de la réunion des deux veines iliaques communes et qui s\'ouvre dans l\'atrium droit (anciennement oreillette droite) du cœur.'
          )
          " />
        <path
          d="M47.1502 45.5481C41.7672 47.1079 39.3116 47.9972 40.1872 49.7259C41.4522 50.5336 43.3548 50.9904 48.5428 51.8148H54.1132C54.1132 51.8148 58.2902 51.1185 58.9873 49.0296C59.6844 46.9407 58.4922 46.1211 54.8095 45.5481C51.9181 45.197 50.2051 45.3226 47.1502 45.5481Z"
          fill="url(#paint8_linear_51_3)" stroke="black" stroke-width="1.3926" />
        <circle cx="132" cy="130" r="5" fill="yellow" stroke="black" stroke-width="1" @click="
          showInfo(
            'heart',
            'Valve Mitrale',
            'La valve mitrale est une des quatre valves du cœur qui permettent au sang de circuler dans la bonne direction. Elle est située entre l\'oreillette gauche et le ventricule gauche du cœur. La valve mitrale est également appelée valve atrio-ventriculaire gauche. Elle est constituée de deux cusps ou volets qui s\'ouvrent et se ferment une fois à chaque battement de cœur. Si la valve ne s\'ouvre ou ne se ferme pas correctement, la circulation sanguine peut être réduite'
          )
          " />
        <defs>
          <linearGradient id="paint0_linear_51_3" x1="61.7707" y1="161.134" x2="116.082" y2="197.341"
            gradientUnits="userSpaceOnUse">
            <stop stop-color="#EDD2AC" />
            <stop offset="0.472356" stop-color="#EDC89B" />
            <stop offset="1" stop-color="#A2582C" />
          </linearGradient>
          <linearGradient id="paint1_linear_51_3" x1="107.727" y1="111.697" x2="117.475" y2="163.919"
            gradientUnits="userSpaceOnUse">
            <stop stop-color="#A54F2A" />
            <stop offset="0.376234" stop-color="#FDDA98" />
            <stop offset="1" stop-color="#A66229" />
          </linearGradient>
          <linearGradient id="paint2_linear_51_3" x1="133.141" y1="106.435" x2="133.141" y2="127.015"
            gradientUnits="userSpaceOnUse">
            <stop stop-color="#D8DEBD" />
            <stop offset="1" stop-color="#F2EAC6" />
          </linearGradient>
          <linearGradient id="paint3_linear_51_3" x1="71.5184" y1="133.282" x2="61.0739" y2="147.904"
            gradientUnits="userSpaceOnUse">
            <stop stop-color="#EFEDD7" />
            <stop offset="1" stop-color="#DBD2AF" />
          </linearGradient>
          <linearGradient id="paint4_linear_51_3" x1="57.605" y1="92.8965" x2="57.593" y2="128.408"
            gradientUnits="userSpaceOnUse">
            <stop stop-color="#927A62" />
            <stop offset="1" stop-color="#CE9773" />
          </linearGradient>
          <linearGradient id="paint5_linear_51_3" x1="128.896" y1="80.3631" x2="128.896" y2="107.519"
            gradientUnits="userSpaceOnUse">
            <stop stop-color="#9F6740" />
            <stop offset="1" stop-color="#E6BA7F" />
          </linearGradient>
          <linearGradient id="paint6_linear_51_3" x1="79.8743" y1="107.519" x2="95.8891" y2="117.963"
            gradientUnits="userSpaceOnUse">
            <stop offset="0.0593933" stop-color="#E2DAEA" />
            <stop offset="1" stop-color="#514B63" />
          </linearGradient>
          <linearGradient id="paint7_linear_51_3" x1="49.9333" y1="46.2444" x2="55.5037" y2="81.0594"
            gradientUnits="userSpaceOnUse">
            <stop stop-color="#6CA3D3" />
            <stop offset="1" stop-color="#6BB6DF" />
          </linearGradient>
          <linearGradient id="paint8_linear_51_3" x1="42.9716" y1="49.0296" x2="58.2902" y2="48.3333"
            gradientUnits="userSpaceOnUse">
            <stop stop-color="#4D7796" />
            <stop offset="0.527149" stop-color="#5D9DCA" />
            <stop offset="1" stop-color="#5385AA" />
          </linearGradient>
        </defs>
      </svg>
    </div>
    <transition name="fade">
      <div class="info-container">
        <div class="title-container">
          <h3 v-if="selectedHeartPart" :class="{ active: selectedHeartPart }">
            {{ selectedHeartPart.name }}
          </h3>
        </div>
        <div class="text-container">
          <p v-if="selectedHeartPart" :class="{ active: selectedHeartPart }">
            {{ selectedHeartPart.description }}
          </p>
        </div>
      </div>
    </transition>
  </div>
  <div class="title-container">
    <h2>Corps</h2>
  </div>
  <div class="wrapper">
    <div class="body-container part-container">
      <svg xmlns="http://www.w3.org/2000/svg" width="160" height="300" viewBox="0 0 160 300" fill="none">
        <g clip-path="url(#clip0_62_13)">
          <path
            d="M91.187 1.6667C73.1174 -1.21852 67.1743 -0.26385 60.4317 3.80355C57.744 5.74214 55.478 8.04206 53.9568 10.2141C47.3696 19.4891 47.2393 25.0752 49.6403 35.3221L58.2734 54.0195C58.2734 54.0195 57.1942 58.2932 57.1942 62.0327V70.5801C18.3453 79.6617 19.5711 82.2197 10.2518 94.6197C7.67966 103.269 8.41696 108.867 9.17266 118.659C5.117 123.571 4.75797 127.58 4.85612 135.22V157.123C1.36924 167.064 0.714435 172.356 0 181.696V247.405V251.144L4.85612 257.555L16.1871 263.431C18.3878 263.371 18.795 262.252 18.3453 258.623L11.3309 251.144V245.268H14.5683V252.212C16.2282 254.286 17.2365 255.087 19.964 252.212V245.268C19.3407 238.266 18.1181 234.772 14.5683 229.241V221.228L18.3453 210.544L26.4389 187.038C26.8902 173.723 27.1789 166.412 29.6763 161.93L32.3741 144.836L33.4532 187.038C30.8858 196.146 29.6593 201.288 28.0576 210.544L29.6763 281.06H69.6043L74.4604 247.405L80.3957 281.06H119.784L120.863 210.544C119.904 201.75 118.629 196.573 115.468 187.038L117.086 144.836L120.863 161.93C121.002 169.011 121.361 173.847 122.482 183.833C125.767 200.151 128.329 208.672 135.971 221.228V229.241C129.887 235.536 128.535 240.72 128.957 252.212C131.153 254.99 132.142 254.316 133.813 252.212L134.892 245.268H137.59V251.144L130.576 258.623C128.696 261.699 129.73 262.504 132.734 263.431C138.864 261.221 141.353 259.929 144.604 257.555C149.181 251.496 149.807 249.746 150 247.405V181.696C149.399 172.579 147.615 166.606 144.604 156.054L143.525 135.22C143.778 126.375 143.225 122.709 140.827 118.659L139.209 94.6197C139.209 85.0039 114.352 76.5828 93.8849 70.5801C92.6503 67.2421 93.0141 65.3708 93.8849 62.0327C104.401 61.7363 109.078 61.3722 108.993 59.3616C108.012 56.6998 108.217 55.6502 108.993 54.0195V50.28H110.612C110.967 45.6171 111.4 44.8344 112.23 43.8695C114.127 43.8695 117.086 45.4721 117.086 43.8695C117.086 42.2668 115.096 38.1068 112.23 35.3221C108.92 32.0258 109.224 30.6949 112.23 28.9115C111.616 22.727 110.86 19.6128 108.993 14.4878C110.984 13.075 110.877 12.1292 108.993 10.2141C103.278 5.59074 99.4486 3.69561 91.187 1.6667Z"
            fill="#FDD5B2" stroke="black" opacity=".2" stroke-width="2" />
          <path
            d="M61.5 220C58.024 222.186 56.8182 223.582 56.5 226.5C52.5626 226.337 52.1759 224.027 51 220.5L50 221C50.6663 225.951 51.7511 227.955 56 229C58.9727 237.535 61.8578 241.114 71.5 243L73 246H75.5L76.5 243C84.1786 241.308 87.9509 238.929 92.5 229L98.5 224L97.5 223C96 224.167 92.8 226.5 92 226.5C91.1119 222.438 89.8747 221.457 87.5 220C77.8109 220.961 72.1593 221.052 61.5 220Z"
            fill="url(#paint0_linear_62_13)" stroke="#F2A812" />
          <path
            d="M65.0215 183.472C68.3088 181.302 69.1228 180.268 70.0233 178.52C72.1979 176.628 73.594 177.492 76.1364 179.621L67.8 188.425C62.5399 189.144 52.4435 192.118 52.2392 192.826C51.1551 194.43 51.1526 195.553 51.6629 197.694C51.9005 197.041 55.7886 192.826 58.3522 192.826C61.131 192.826 61.9474 193.098 63.354 195.027C65.2465 192.872 66.3356 191.766 68.9116 191.726C71.7301 191.777 73.1288 192.273 74.4691 196.128C76.2437 192.948 77.2631 190.562 78.9151 190.625H83.3612C84.9802 193.554 85.8809 195.083 87.2515 195.027C88.4832 195.205 89.6767 193.843 92.2533 190.075H96.6993C98.857 189.882 99.4292 191.564 99.4781 197.228C99.4854 198.612 100.355 199.16 103.368 199.753C103.806 202.205 104.384 203.58 103.368 206.032C102.863 207.18 101.19 207.225 97.8108 207.133C97.4407 205.731 96.4522 205.385 93.3648 205.482C92.4887 207.638 92.164 209.003 92.2533 212.085L86.14 212.635C85.1569 212.661 84.6805 211.68 83.9169 208.783H82.2497C81.7434 211.755 81.1181 213.311 77.8036 215.386H73.9133C71.8782 209.239 71.2055 209.035 70.0233 208.783C68.6656 208.644 68.0154 209.38 67.2443 213.736H61.6867C60.4923 211.525 59.8651 210.085 58.3522 209.334C57.5189 208.697 56.5798 209.571 53.9062 213.736H45.5698V209.334H52.2392L53.3504 207.133C56.1389 202.655 57.404 200.983 58.3522 201.63C61.3062 203.268 62.3706 204.396 62.2425 207.133H65.0215C67.0339 203.67 68.1546 201.771 69.4673 202.18C72.8253 205.19 74.1472 206.791 74.4691 209.334C75.8926 210.698 76.7599 210.637 78.3594 209.334V204.932C79.8983 201.617 80.5824 198.329 82.2497 199.98C83.9169 201.63 86.1832 203.144 86.14 206.032L87.8072 204.381C88.0112 203.416 88.5355 202.673 90.0303 201.08C93.2861 200.616 94.2375 200.259 94.4763 199.429C93.2315 198.816 93.1503 198.121 93.3648 196.678C90.2447 197.957 89.3229 198.985 88.363 201.08H85.5842C83.8691 198.306 82.9111 196.583 81.1382 196.678C79.1698 196.317 78.6449 198.299 77.8036 202.18H72.2461C70.4491 198.013 69.7409 197.027 68.9116 197.228C67.5018 197.256 66.8002 198.796 65.577 202.18H61.6867C59.5877 200.925 59.4339 200.014 59.4637 198.329H57.2407C56.4322 201.161 55.5236 202.52 50.5716 203.281C47.034 202.715 46.4245 201.028 46.6816 196.678C46.6223 192.943 47.4072 190.958 52.2392 187.874C57.3132 185.892 60.2128 184.602 65.0215 183.472Z"
            fill="#FC726D" stroke="#E5786B" stroke-width="1.03" />
          <path
            d="M108.5 151.841C106.608 149.43 105.414 149.342 103 151.841C103 151.841 106.5 154.341 106.5 157.841C106.5 161.341 106 163.841 106 163.841C106 163.841 106.5 164.841 108 165.341C109.5 165.841 111.012 164.592 112 162.841C113.134 160.952 112.594 160.355 111.5 159.341C113.5 157.341 110.5 155.341 110.5 155.341C111.191 152.98 110.834 152.172 108.5 151.841Z"
            fill="url(#paint1_linear_62_13)" stroke="#DC26CC" />
          <path
            d="M50.5725 226.391H47.7937C47.8457 221.237 46.8045 219.662 43.9028 218.137H39.4568C36.6976 215.937 35.7032 213.841 35.0122 208.233C34.2955 200.682 35.4048 199.543 37.7901 198.329V196.128C35.0193 190.362 35.5641 187.528 41.6804 183.472C44.5146 181.939 46.4118 181.138 52.2397 180.171H59.4646C61.9855 180.384 63.2653 180.901 65.0221 183.472C65.742 180.648 67.4382 179.379 71.6912 177.42C75.1968 178.042 77.0041 178.546 77.8045 181.822H80.5833C82.5631 180.551 83.7334 179.864 89.4754 180.171C91.2861 180.054 92.272 180.518 93.9214 184.023H97.2559C97.6806 181.755 98.52 181.021 101.146 180.721C104.752 180.893 106.535 181.653 108.927 185.123V192.826C113.533 195.178 113.843 198.039 113.373 203.831C111.123 204.479 109.927 205.57 107.815 207.683C107.62 211.899 106.456 213.146 103.369 214.286C101.614 215.239 97.7872 215.155 97.2559 214.286C95.4319 213.182 94.4454 212.951 92.8099 214.286C92.3808 215.98 91.8262 216.795 90.5869 218.137C86.7384 219.283 84.2496 219.167 79.4718 218.137V225.29L77.2487 227.491V230.243C78.9133 231.088 79.3422 232.634 79.4718 236.78C80.1401 243.38 79.5334 248.185 74.4693 253.287C70.0458 248.368 69.5854 243.386 69.4682 236.78C69.63 235.08 70.0807 231.169 72.8027 230.243V227.491C70.7157 227.039 70.1124 226.491 69.4682 225.29C69.0125 221.491 69.4553 219.942 71.6912 218.137C73.1732 217.771 76.2484 217.037 76.693 217.037C76.9662 214.783 78.3661 214.054 80.5833 212.635C84.1502 211.209 86.2655 210.869 90.5869 212.635L92.2541 210.984L95.0329 207.683C99.0888 206.664 101.418 206.396 105.592 206.582V203.831C103.024 201.172 102.592 199.59 102.813 196.678L105.592 193.927V190.625L100.035 189.525L96.7002 187.324H93.9214L91.1426 189.525H85.0293L81.139 184.573H79.4718L75.5815 187.874H61.6876C56.8059 188.284 54.3114 187.885 50.0167 186.774C48.2103 190.551 46.3267 192.593 41.6804 196.128V198.329L45.5707 202.18C45.7993 206.98 45.5439 209.609 45.0149 214.286C46.1264 216.487 50.2597 218.013 50.5725 219.788V226.391Z"
            fill="#D4787E" stroke="#E5786B" stroke-width="1.03" />
          <path
            d="M71.1348 248.18L74.4137 253.375L78.3485 248.18C78.3485 248.18 77.6927 245.583 74.4137 245.583C71.1348 245.583 71.1348 248.18 71.1348 248.18Z"
            fill="#782C2C" stroke="#000B20" stroke-width="1.2154" />
          <path
            d="M83.9174 168.616L65.0218 169.166C62.0389 170.058 60.8352 171.375 58.9084 174.118C58.5576 176.271 59.1161 177.081 61.1315 177.97C69.9318 178.337 74.3145 177.873 80.5829 175.219C85.4989 172.316 85.9861 170.893 83.9174 168.616Z"
            fill="#F59516" stroke="#FC802E" stroke-width="1.03" />
          <path
            d="M91.6959 142.755C89.8289 145.658 85.0288 144.405 86.1384 147.157C87.248 149.908 85.8916 152.645 75.581 165.314C73.4669 166.989 71.9811 167.283 68.91 166.965C67.1192 171.698 66.2857 174.291 68.91 177.42C72.0514 177.35 73.8886 177.586 77.8021 180.171C87.8004 179.575 91.5483 177.679 96.6977 173.018C106.233 164.558 108.054 159.73 106.701 151.008C103.427 143.959 100.179 142.092 91.6959 142.755Z"
            fill="#FC766C" fill-opacity="0.53" stroke="#F48677" stroke-width="1.03" />
          <path
            d="M56.129 147.707H41.1236C36.4092 148.757 35.4893 150.477 35.0103 154.31V166.965C36.9089 175.27 38.1086 179.481 41.6793 182.372C46.9613 182.619 49.5211 182.434 51.6829 180.171C57.5058 174.241 60.9303 170.994 68.3556 165.865C72.055 165.564 73.8792 165.265 75.0246 163.664C80.9144 156.032 86.0996 150.034 85.584 148.257C84.8714 146.566 84.3007 145.735 82.2495 144.956L66.6883 142.755C61.1506 143.932 59.1078 145.161 56.129 147.707Z"
            fill="#C94C46" stroke="#CB6A5A" stroke-width="1.03" />
          <path
            d="M45.5698 161.065V164.367C49.1952 166.026 50.1013 166.111 54.4619 164.367C54.4619 164.367 55.0177 168.769 56.1292 169.869C57.2407 170.97 60.5752 172.07 60.5752 172.07L61.6867 169.869L60.0195 169.319C57.5158 167.5 57.5408 166.38 57.7964 164.367L60.5752 157.764C61.0517 155.362 60.5806 155.031 58.908 155.563L56.1292 161.616L52.7946 158.864C48.5716 158.4 46.9952 158.887 45.5698 161.065Z"
            fill="#2E5154" stroke="#975757" stroke-width="1.03" />
          <path
            d="M71.6904 142.755V39.8599C76.3511 40.0778 78.9747 40.1988 78.9153 40.9604L79.471 65.1709H78.3595C77.0356 63.249 75.9153 62.7902 73.3577 62.9699V66.2714L79.471 69.0226L80.5825 144.405L71.6904 142.755Z"
            fill="#FB776C" stroke="#F8BE99" stroke-width="1.03" />
          <path
            d="M102.257 44.2617C93.5733 41.8807 88.7092 42.091 80.0269 44.2617V53.0656C83.929 52.1657 86.2909 51.7021 92.8092 51.4149C98.6747 51.7178 101.23 52.1175 105.036 53.0656C107.613 52.6483 107.94 51.7634 107.815 49.7642C106.847 46.7833 105.58 45.6004 102.257 44.2617Z"
            fill="#D16069" stroke="#EA8078" stroke-width="1.03" />
          <path
            d="M62.7983 33.8073V40.9604C66.5086 43.1768 67.9368 42.8636 68.9116 38.7594C73.3293 38.5974 75.7667 38.5552 79.471 39.3097L83.3613 42.0608L86.1401 41.5106C81.6344 37.3478 79.2479 36.5383 75.025 35.458H68.9116C69.0154 33.9374 69.4164 32.995 71.1347 31.0561C71.9233 29.3542 70.9587 28.9332 68.9116 28.3049L62.7983 33.8073Z"
            fill="#F3931B" />
          <path
            d="M86.6958 55.2666C86.5523 53.7723 87.2671 53.2087 89.4746 52.5154H94.4764V55.8168H90.5861L86.1401 60.2187H88.3631C90.0626 60.2635 90.0483 61.2397 89.4746 63.5202C87.5501 64.4574 86.0293 64.6509 82.8055 64.6207C80.9629 63.4361 80.5716 62.1003 81.1383 58.568H85.5843L88.3631 55.8168L86.6958 55.2666Z"
            fill="#F3931B" />
          <path
            d="M62.7983 33.8073V40.9604C66.5086 43.1768 67.9368 42.8636 68.9116 38.7594C73.3293 38.5974 75.7667 38.5552 79.471 39.3097L83.3613 42.0608L86.1401 41.5106C81.6344 37.3478 79.2479 36.5383 75.025 35.458H68.9116C69.0154 33.9374 69.4164 32.995 71.1347 31.0561C71.9233 29.3542 70.9587 28.9332 68.9116 28.3049L62.7983 33.8073Z"
            stroke="#ECBB70" stroke-width="1.03" />
          <path
            d="M86.6958 55.2666C86.5523 53.7723 87.2671 53.2087 89.4746 52.5154H94.4764V55.8168H90.5861L86.1401 60.2187H88.3631C90.0626 60.2635 90.0483 61.2397 89.4746 63.5202C87.5501 64.4574 86.0293 64.6509 82.8055 64.6207C80.9629 63.4361 80.5716 62.1003 81.1383 58.568H85.5843L88.3631 55.8168L86.6958 55.2666Z"
            stroke="#ECBB70" stroke-width="1.03" />
          <path
            d="M86.2966 129.825L103.846 137.225C103.846 137.225 105.471 137.869 105.471 139.478V157.175H106.771L105.471 159.588L105.796 184.679C105.796 188.847 101.896 188.847 101.896 188.847H88.2465L77.8469 193.855H75.897V192.568L77.5219 192.247L75.897 191.925V190.959H79.7968L84.3466 188.847L81.4217 188.707L77.1969 190.316H75.897V189.458L77.5219 188.847H75.897V188.064H78.4969L80.4468 187.42L79.4718 186.777L77.8469 187.098L75.897 187.42V186.777L77.5219 186.133H75.897V185.168H78.4969L81.0968 186.133H84.6716L80.1218 183.881H77.8469L75.897 184.203V182.915H77.8469L75.897 182.272V180.985C75.897 180.985 77.1969 180.985 77.8469 181.307C78.4969 181.628 88.2465 186.133 88.2465 186.133H101.896C103.196 186.133 103.196 184.679 103.196 184.679V160.392L101.246 157.175H102.871V139.478L85.3216 132.077L86.2966 129.825Z"
            fill="#F90304" />
          <path
            d="M103.196 160.392L104.171 162.001L105.471 159.588M103.196 160.392L101.246 157.175H102.871V139.478L85.3216 132.077L86.2966 129.825L103.846 137.225C103.846 137.225 105.471 137.869 105.471 139.478V157.175H106.771L105.471 159.588M103.196 160.392V184.679C103.196 184.679 103.196 186.133 101.896 186.133H88.2465C88.2465 186.133 78.4969 181.628 77.8469 181.307C77.1969 180.985 75.897 180.985 75.897 180.985V182.272L77.8469 182.915H75.897V184.203L77.8469 183.881H80.1218L84.6716 186.133H81.0968L78.4969 185.168H75.897V186.133H77.5219L75.897 186.777V187.42L77.8469 187.098L79.4718 186.777L80.4468 187.42L78.4969 188.064H75.897V188.847H77.5219L75.897 189.458V190.316H77.1969L81.4217 188.707L84.3466 188.847L79.7968 190.959H75.897V191.925L77.5219 192.247L75.897 192.568V193.855H77.8469L88.2465 188.847H101.896C101.896 188.847 105.796 188.847 105.796 184.679L105.471 159.588"
            stroke="black" stroke-width="0.602309" />
          <path
            d="M65.5767 122.33L45.6733 114.702C45.6733 114.702 42.0984 112.772 42.0984 116.633V138.834V158.462L43.3984 157.198L41.1234 162H42.0984V186.011C42.0984 186.011 42.0984 188.711 45.0233 188.572L49.2481 188.711H62.8976L73.2971 193.695H75.2471V192.414L73.6221 192.094L75.2471 191.774V190.813H71.3472L66.7974 188.711L69.7223 188.572L73.9471 190.173H75.2471V189.319L73.6221 188.711H75.2471V187.932H72.6472L70.6973 187.292L71.6722 186.651L73.2971 186.972L75.2471 187.292V186.651L73.6221 186.011H75.2471V185.051H72.6472L70.0473 186.011H66.4724L71.0222 183.77H73.2971L75.2471 184.09V182.81H73.2971L75.2471 182.169V180.889C75.2471 180.889 73.9471 180.889 73.2971 181.209C72.6472 181.529 62.8976 186.011 62.8976 186.011H49.2481H45.0233V162H46.3232L43.3984 157.198L45.0233 158.462L44.3733 116.633L65.021 123.981L65.5767 122.33Z"
            fill="#0B0C82" />
          <path
            d="M42.0984 138.834V158.462L43.3984 157.198M42.0984 138.834C42.0984 137.709 42.0984 120.494 42.0984 116.633M42.0984 138.834V116.633M43.3984 157.198L45.0233 158.462L44.3733 116.633L65.021 123.981L65.5767 122.33L45.6733 114.702C45.6733 114.702 42.0984 112.772 42.0984 116.633M43.3984 157.198L46.3232 162H45.0233M43.3984 157.198L41.1234 162H42.0984M45.0233 162V186.011H49.2481H62.8976C62.8976 186.011 72.6472 181.529 73.2971 181.209C73.9471 180.889 75.2471 180.889 75.2471 180.889V182.169L73.2971 182.81H75.2471V184.09L73.2971 183.77H71.0222L66.4724 186.011H70.0473L72.6472 185.051H75.2471V186.011H73.6221L75.2471 186.651V187.292L73.2971 186.972L71.6722 186.651L70.6973 187.292L72.6472 187.932H75.2471V188.711H73.6221L75.2471 189.319V190.173H73.9471L69.7223 188.572L66.7974 188.711L71.3472 190.813H75.2471V191.774L73.6221 192.094L75.2471 192.414V193.695H73.2971L62.8976 188.711H49.2481L45.0233 188.572C42.0984 188.711 42.0984 186.011 42.0984 186.011V162M45.0233 162H42.0984"
            stroke="black" stroke-width="0.602309" />
          <path
            d="M79.1473 114.702C75.5724 114.059 72.0203 114.838 69.3977 116.633C66.6946 118.962 65.7874 119.907 65.4978 120.816C64.4853 125.964 64.6685 127.803 66.1478 129.503L70.6976 134.008C73.53 136.77 77.5223 138.191 79.7973 137.869C82.0722 137.547 85.3146 132.734 85.972 129.825C87.2562 122.645 82.7221 115.346 79.1473 114.702Z"
            fill="url(#paint2_linear_62_13)" stroke="black" stroke-width="0.602309" />
          <path
            d="M73.2971 119.529C72.5888 118.254 72.3221 117.276 70.6972 117.276C69.0723 117.276 67.2493 120.404 66.7974 122.424C66.8972 125.252 66.9368 126.867 68.7473 126.607C71.6554 126.238 72.922 125.807 74.597 124.677C74.7092 123.348 73.6221 123.39 73.6221 122.103C73.6221 120.816 73.6654 120.297 73.2971 119.529Z"
            fill="#01046E" stroke="black" stroke-width="0.602309" />
          <path
            d="M78.1721 124.998C77.4899 125.419 77.4505 125.721 77.5221 126.286C77.5221 126.286 80.1219 134.008 81.0968 134.651C82.0718 135.295 82.9186 132.823 83.3717 131.434C84.5191 125.881 85.0891 122.96 84.0217 123.39L78.1721 124.998Z"
            fill="#FA0102" stroke="black" stroke-width="0.602309" />
          <path
            d="M68.4234 128.538C67.7731 129.182 69.6881 130.348 70.0485 130.79C70.0485 130.79 76.3151 135.748 77.4862 135.788C78.6572 135.828 78.0657 133.285 77.7135 131.867C75.742 126.546 74.9228 126.607 72.9729 126.607C71.0231 126.607 69.0737 127.895 68.4234 128.538Z"
            fill="#01046E" stroke="black" stroke-width="0.602309" />
          <path
            d="M83.6965 122.103C82.8226 123.15 76.5468 124.033 76.5468 124.033L73.6219 118.242C72.8926 116.75 73.5256 116.166 75.5719 115.346C77.8066 115.307 78.9793 115.737 80.7716 117.276C83.5389 119.878 84.5704 121.055 83.6965 122.103Z"
            fill="#FA0102" stroke="black" stroke-width="0.602309" />
          <path
            d="M77.3823 77.2152H73.97C71.922 77.2152 73.312 86.9441 71.9231 85.9994C68.5002 81.5668 67.4773 81.0547 66.4628 81.9452C54.1395 91.5881 52.8129 109.649 53.4958 113.703C54.1788 117.757 56.5741 121.07 58.9556 120.46C63.9772 119.295 66.2013 117.836 69.1927 113.703C73.8398 106.152 73.3081 101.542 73.2875 93.4321C75.239 89.8136 76.4035 89.1919 78.7473 93.4321C79.6401 105.936 80.2869 111.38 82.1597 113.703C85.1409 118.19 92.3967 121.136 94.4442 120.46C96.4916 119.784 99.1057 108.917 98.539 105.595C90.8776 84.5417 87.9606 80.36 84.8895 81.9452C83.6786 82.8553 83.0443 83.4146 82.1597 84.648C80.7235 86.715 79.9442 87.2353 78.7473 84.6479C78.7476 80.2734 79.021 77.0654 77.3823 77.2152Z"
            fill="#82BEF3" stroke="#000B20" stroke-width="1.26485" />
          <path
            d="M76.5467 83.8131H78.4966L89.2212 88.6395H103.521C104.835 88.6989 105.499 88.8183 105.47 90.5701V97.6488H107.095L104.171 102.797L105.47 101.832V107.945C105.447 108.544 105.219 108.888 103.521 109.554L84.3464 118.563L82.7214 117.276L102.871 107.623V101.832L104.171 102.797L101.896 97.6488H103.196V90.5701H89.2212L78.4966 95.7182H76.5467V95.0747L77.8466 94.753V94.1094H76.2217V93.1442H78.8216L80.4465 93.4659L85.3213 90.8918H81.7465L78.1716 92.5006H76.2217V91.5353H78.1716L78.8216 90.8918H76.2217V89.9265H81.0965L79.7965 89.283H76.2217V88.3177H77.8466L76.2217 87.3525V86.3872L79.4715 87.0307L82.3964 88.3177H84.9963L81.4215 86.3872L76.2217 85.4219L77.8466 85.1001L76.5467 84.7784V83.8131Z"
            fill="#EF2124" />
          <path
            d="M75.572 83.8131H73.6221L62.8975 88.6395H48.5981C47.2838 88.6989 46.6197 88.8183 46.6482 90.5701L46.8106 100.062L45.6732 102.475H46.6482V107.945C46.6714 108.544 46.8999 108.888 48.5981 109.554L67.7723 118.563L69.3972 117.276L49.2481 107.623V102.475H50.548L49.2481 100.062L48.9231 90.5701H62.8975L73.6221 95.7182H75.572V95.0747L74.272 94.753V94.1094H75.897V93.1442H73.2971L71.6721 93.4659L66.7973 90.8918H70.3722L73.9471 92.5006H75.897V91.5353H73.9471L73.2971 90.8918H75.897V89.9265H71.0222L72.3221 89.283H75.897V88.3177H74.272L75.897 87.3525V86.3872L72.6471 87.0307L69.7222 88.3177H67.1223L70.6972 86.3872L75.897 85.4219L74.272 85.1001L75.572 84.7784V83.8131Z"
            fill="#0B0C82" />
        </g>
        <defs>
          <linearGradient id="paint0_linear_62_13" x1="58.5" y1="228.5" x2="91" y2="229.5"
            gradientUnits="userSpaceOnUse">
            <stop stop-color="#F47901" />
            <stop offset="0.511821" stop-color="#F8AF08" />
            <stop offset="1" stop-color="#FC7A03" />
          </linearGradient>
          <linearGradient id="paint1_linear_62_13" x1="107.815" y1="150" x2="107.815" y2="165.452"
            gradientUnits="userSpaceOnUse">
            <stop stop-color="#DC26CC" />
            <stop offset="1" stop-color="#76146D" />
          </linearGradient>
          <linearGradient id="paint2_linear_62_13" x1="75.5285" y1="114.479" x2="75.5285" y2="137.914"
            gradientUnits="userSpaceOnUse">
            <stop stop-color="#EC3E40" />
            <stop offset="1" stop-color="#862324" />
          </linearGradient>
          <clipPath id="clip0_62_13">
            <rect width="160" height="300" fill="white" />
          </clipPath>
        </defs>
        <circle cx="72" cy="155" r="5" fill="yellow" stroke="black" stroke-width="1" @click="
          showInfo(
            'body',
            'Foie',
            'Décompose l\'alcool, les drogues et les autres toxines présentes dans le sang afin que ces substances puissent être évacuées du corps par les selles ou l\'urine'
          )
          " />
        <!-- FOIE -->
        <circle cx="55" cy="164" r="4" fill="yellow" stroke="black" stroke-width="1" @click="
          showInfo(
            'body',
            'Vésicule Biliaire',
            'La vésicule biliaire est une petite poche située sous le foie. Son rôle consiste à stocker la bile avant qu\'elle se déverse dans l\'intestin, ce qui arrive en particulier au moment de la digestion. Sécrétée par le foie, la bile est un liquide qui facilite la digestion des graisses.'
          )
          " />
        <!-- VESICULE BILIAIRE -->
        <circle cx="95" cy="162" r="4" fill="yellow" stroke="black" stroke-width="1" @click="
          showInfo(
            'body',
            'Estomac',
            'Organe long et tubulaire dans l\'abdomen qui reçoit la nourriture partiellement digérée de l\'estomac, absorbe les éléments nutritifs et rejette les aliments digérés dans le gros intestin.'
          )
          " />
        <!-- ESTOMAC -->
        <circle cx="72" cy="173" r="4" fill="yellow" stroke="black" stroke-width="1" @click="
          showInfo(
            'body',
            'Pancreas',
            'Pendant la digestion, le pancréas fabrique des sucs pancréatiques appelés enzymes. Ces enzymes décomposent les sucres, les graisses et les amidons. Le pancréas aide également le système digestif en produisant des hormones. Ce sont des messagers chimiques qui circulent dans le sang.'
          )
          " />
        <!-- PANCREAS -->
        <circle cx="109" cy="159" r="3" fill="yellow" stroke="black" stroke-width="1" @click="
          showInfo(
            'body',
            'Ratte',
            'Le rôle de la rate, longtemps méconnu, est extrêmement important. En effet, il s\'agit d\'un organe lymphoïde, c\'est-à-dire qu\'il stocke les lymphocytes et les monocytes, des cellules qui assurent la protection de l\'organisme (système immunitaire).'
          )
          " />
        <!-- RATTE -->
        <circle cx="111" cy="156" r="2" fill="green" stroke="black" stroke-width="1" @click="
          showInfo(
            'body',
            'Hypochondre gauche',
            'Sur l\'hypocondre gauche se projettent : la rate, l\'estomac et l\'angle gauche du côlon.'
          )
          " />
        <!-- HYPOCHONDRE GAUCHE -->
        <circle cx="40" cy="210" r="4" fill="yellow" stroke="black" stroke-width="1" @click="
          showInfo(
            'body',
            'Gros intestin',
            'La grande majorité des substances digestibles ont été absorbées dans l\'intestin grêle, seules l\'eau et les matières indigestes se retrouvent à l\'entrée du gros intestin. Son premier travail est de récupérer l\'eau qui reste dans ces matières indigestes, puis de compacter celles-ci sous la forme de selles.'
          )
          " />
        <!-- GROS INSTESTIN -->
        <circle cx="69" cy="208" r="4" fill="yellow" stroke="black" stroke-width="1" @click="
          showInfo(
            'body',
            'Intestin grêle',
            'Ces régions de l\'intestin grêle participent largement à l\'absorption des graisses et autres nutriments. Les mouvements digestifs facilitent l\'absorption, elle-même renforcée par la grande surface de contact formée par les replis, villosités et microvillosités.'
          )
          " />
        <!-- INSTESTIN GRELE -->
        <circle cx="75" cy="250" r="2" fill="yellow" stroke="black" stroke-width="1" @click="
          showInfo(
            'body',
            'Rectum',
            'Le rectum est un lieu de rétention des selles . Lorsqu\'il est plein, il expulse les selles hors du corps par l\'anus.'
          )
          " />
        <!-- RECTUM -->
        <circle cx="67" cy="228" r="3" fill="yellow" stroke="black" stroke-width="1" @click="
          showInfo(
            'body',
            'Vessie',
            'Sert à emmagasiner l\'urine avant qu\'elle ne soit évacuée du corps. La vessie a une paroi élastique, ce qui lui permet de grossir (se dilater) à mesure qu\'elle se remplit d\'urine, et de rétrécir (se contracter) lorsqu\'elle se vide.'
          )
          " />
        <!-- VESSIE -->
        <circle cx="50" cy="227" r="3" fill="yellow" stroke="black" stroke-width="1" @click="
          showInfo(
            'body',
            'Appendice',
            'Le rôle de l\'appendice n\'est pas totalement élucidé, mais il pourrait intervenir dans le système immunitaire. L\'appendice abriterait une flore bactérienne bénéfique qui serait tenue en réserve pour répondre à une indigestion grave. Elle peut parfois mener à une inflammation (appendicite) nécessitant son ablation (appendicectomie)'
          )
          " />
        <!-- APPENDICE -->
        <circle cx="65" cy="104" r="3" fill="yellow" stroke="black" stroke-width="1" @click="
          showInfo(
            'body',
            'Poumons',
            'Les principales fonctions des poumons sont de transférer dans le sang l\'oxygène présent dans l\'air et d\'évacuer dans l\'air le dioxyde de carbone présent dans le sang. L\'air entre par la bouche ou le nez et descend dans la trachée, les bronches et les bronchioles jusqu\'aux alvéoles.'
          )
          " />
        <!-- POUMONS -->
        <circle cx="76" cy="53" r="3" fill="yellow" stroke="black" stroke-width="1" @click="
          showInfo(
            'body',
            'Œsophage',
            'L\'œsophage est le premier segment du tube digestif qui a pour fonction le transport des aliments mâchés. Ce tube musculeux s\'étend du larynx jusqu\'à l\'estomac, où la nourriture est digérée. La digestion commence de manière mécanique, par la contracture des muscles de l\'estomac.'
          )
          " />
        <!-- OEUSOPHAGE -->
        <circle cx="76" cy="66" r="2" fill="yellow" stroke="black" stroke-width="1" @click="
          showInfo(
            'body',
            'Clapet',
            'Le sphincter inférieur de l\'œsophage est un muscle situé entre l\'œsophage et l\'estomac. Il permet d\'ouvrir et de fermer l\'entrée dans l\'estomac. Chez de nombreuses personnes il peut disfonctionner, menant à des remontées acides et une sensation d\'inconfort plus ou moins intense.'
          )
          " />
        <!-- CLAPET -->
        <circle cx="94" cy="47" r="3" fill="yellow" stroke="black" stroke-width="1" @click="
          showInfo(
            'body',
            'Langue',
            'La langue, organe important de la cavité buccale, sert tant à la déglutition, qu\'à la mastication, à la gustation et au langage.'
          )
          " />
        <!-- LANGUE -->
        <circle cx="66" cy="37" r="2" fill="yellow" stroke="black" stroke-width="1" @click="
          showInfo(
            'body',
            'Glandes salivaires',
            'Les glandes salivaires jouent un rôle important dans la digestion puisqu\'elles produisent de la salive. La salive aide à humidifier la nourriture afin qu\'on puisse l\'avaler plus facilement. Elle contient aussi une enzyme appelée amylase qui aide l\'estomac à décomposer plus facilement l\'amidon provenant des aliments.'
          )
          " />
        <!-- GLANDES SALIVAIRES -->
        <circle cx="117" cy="210" r="2" fill="green" stroke="black" stroke-width="1"
          @click="showInfo('body', 'Flanc gauche', 'Zone du colon descendant')" />
        <!-- FLANC GAUCHE -->
        <circle cx="32" cy="210" r="2" fill="green" stroke="black" stroke-width="1"
          @click="showInfo('body', 'Flanc droit', 'Zone du colon ascendant')" />
        <!-- FLANC DROIT -->
        <circle cx="50" cy="180" r="2" fill="green" stroke="black" stroke-width="1" @click="
          showInfo(
            'body',
            'Hypochondre droit',
            'Zone regroupant le foie, la vésicule biliaire et le duodénum (première partie de l\'intestin grêle)'
          )
          " />
        <!-- HYPOCHONDRE DROIT -->
        <circle cx="88" cy="172" r="2" fill="green" stroke="black" stroke-width="1" @click="
          showInfo(
            'body',
            'Epigastre',
            'Organe musculaire creux situé dans l\'abdomen qui reçoit la nourriture qui passe par l\'oesophage. L\'estomac secrète des sucs digestifs qui sont mélangés à la nourriture afin de la transformer en un liquide clair qui, ensuite, est expulsé vers le duodénum'
          )
          " />
        <!-- EPIGASTRE -->
        <circle cx="84" cy="248" r="2" fill="green" stroke="black" stroke-width="1" @click="
          showInfo(
            'body',
            'Fosse iliaque gauche',
            'La fosse iliaque gauche est occupée essentiellement par les côlons descendant et sigmoïde et par les l\'ovaire gauche chez la femme'
          )
          " />
        <!-- FOSSE ILIAQUE GAUCHE -->
        <circle cx="64" cy="248" r="2" fill="green" stroke="black" stroke-width="1" @click="
          showInfo(
            'body',
            'Fosse iliaque droite',
            'La fosse iliaque droite est occupée essentiellement par le Caecum (Première partie du côlon, et constitue un organe appartenant au système digestif de la plupart des mammifères), l\'appendice et l\'ovaire droit chez la femme'
          )
          " />
        <!-- FOSSE ILIAQUE DROITE -->
        <circle cx="88" cy="172" r="2" fill="green" stroke="black" stroke-width="1" @click="
          showInfo(
            'body',
            'Hypogastre',
            'Zone regroupant la vessie et l\'utérus chez la femme'
          )
          " />
        <!-- HYPOGASTRE -->
      </svg>
    </div>
    <transition name="fade">
      <div class="info-container">
        <div class="title-container">
          <h3 v-if="selectedBodyPart" :class="{ active: selectedBodyPart }">
            {{ selectedBodyPart.name }}
          </h3>
        </div>
        <div class="text-container">
          <p v-if="selectedBodyPart" :class="{ active: selectedBodyPart }">
            {{ selectedBodyPart.description }}
          </p>
        </div>
      </div>
    </transition>
  </div>
    <div class="title-container">
      <h2>Os</h2>
    </div>
    <div class="wrapper">
      <div class="bones-container part-container">
        <svg xmlns="http://www.w3.org/2000/svg" width="154" height="351" viewBox="0 0 154 351" fill="none">
          <path opacity="0.3"
            d="M65.1076 120.556C64.4717 114.511 67.1958 108.867 68.8646 108.45C70.5335 108.032 70.4396 110.815 70.1161 112.207C74.9634 114.865 77.8087 115.742 83.8919 112.624V108.45L86.3966 107.615L88.0664 109.702C90.4325 114.586 90.6282 117.447 90.1537 122.643L86.8141 132.662C79.4072 134.504 75.4685 134.507 68.4462 132.662C66.4339 128.253 65.8681 125.527 65.1076 120.556Z"
            fill="url(#paint0_linear_78_256)" stroke="#B18944" stroke-width="0.8349" />
          <path
            d="M73.8728 120.138L72.6204 119.721C70.7851 120.213 70.5224 120.778 70.1157 121.808C72.0326 121.627 72.8406 121.246 73.8728 120.138ZM73.8728 120.138C76.1864 121.083 77.6287 121.318 80.9694 120.138L82.2218 119.93M82.2218 119.93L83.4741 119.721C84.695 120.264 85.2235 120.672 85.5614 121.808C83.984 121.954 81.798 120.721 82.2218 119.93Z"
            stroke="black" stroke-width="0.8349" />
          <path
            d="M74.2907 126.4L73.0384 125.983C71.203 126.475 70.9404 127.04 70.5337 128.07C72.4506 127.889 73.2586 127.508 74.2907 126.4ZM74.2907 126.4C76.6043 127.345 78.0466 127.58 81.3874 126.4L82.6397 126.191M82.6397 126.191L83.8921 125.983C85.113 126.526 85.6415 126.934 85.9793 128.07C84.402 128.216 82.216 126.982 82.6397 126.191Z"
            stroke="black" stroke-width="0.8349" />
          <path
            d="M75.7185 129.967L74.917 129.7C73.7423 130.015 73.5743 130.377 73.314 131.036C74.5408 130.92 75.0579 130.676 75.7185 129.967ZM75.7185 129.967C77.1992 130.572 78.1223 130.722 80.2603 129.967L81.0618 129.834M81.0618 129.834L81.8633 129.7C82.6447 130.048 82.9829 130.309 83.1992 131.036C82.1896 131.13 80.7906 130.34 81.0618 129.834Z"
            stroke="black" stroke-width="0.534336" />
          <path
            d="M118.123 136.836C114.02 136.863 112.391 135.74 110.609 131.827C107.232 133.091 106.644 134.925 106.434 138.924H98.9199L105.599 140.593C109.136 143.842 110.331 145.853 109.356 150.195C115.095 144.067 117.281 141.04 118.123 136.836Z"
            fill="#EAC080" stroke="#B18944" stroke-opacity="0.24" stroke-width="0.8349" />
          <path
            d="M36.9535 136.836C41.0949 136.863 42.7402 135.74 44.5394 131.827C47.9488 133.091 48.5422 134.925 48.7539 138.924H56.3398L49.5968 140.593C46.0262 143.842 44.8192 145.853 45.8038 150.195C40.0104 144.067 37.8036 141.04 36.9535 136.836Z"
            fill="#EAC080" stroke="#B18944" stroke-opacity="0.24" stroke-width="0.8349" />
          <path
            d="M100.59 132.244L98.085 138.924H106.434C106.756 135.128 107.286 133.272 110.608 131.827C111.336 130.67 111.365 129.924 111.026 128.487C104.731 127.5 102.024 127.861 100.59 132.244Z"
            fill="url(#paint1_linear_78_256)" stroke="#B18944" stroke-opacity="0.5" stroke-width="0.8349" />
          <path
            d="M54.67 132.154L56.3398 139.323H48.826C48.5039 135.249 47.9743 133.257 44.6517 131.706C43.9244 130.464 43.895 129.664 44.2342 128.121C50.5292 127.061 53.2362 127.449 54.67 132.154Z"
            fill="url(#paint2_linear_78_256)" stroke="#B18944" stroke-width="0.8349" />
          <path
            d="M62.6018 140.593C61.9356 138.976 62.1611 138.178 63.0193 136.836C64.3235 135.384 62.0741 135.926 56.3401 137.671C55.9462 139.122 55.3867 139.943 53.418 141.428C53.5311 143.671 53.9249 144.784 56.3401 146.02V151.03C56.3401 155.622 64.2717 155.204 64.2717 155.204C68.4462 155.204 71.3683 151.03 71.3683 151.03C71.8191 149.205 72.8149 148.305 75.5428 146.855V138.924H68.8636C69.5001 140.408 69.4806 141.612 69.2811 143.933C67.525 147.936 66.295 148.247 63.8542 146.855C64.0896 144.265 63.8085 142.897 62.6018 140.593Z"
            fill="url(#paint3_linear_78_256)" stroke="#B18944" stroke-width="0.8349" />
          <path
            d="M92.2409 140.596C92.9072 138.979 92.6817 138.182 91.8235 136.841C90.5192 135.39 92.7687 135.931 98.5027 137.676C98.8966 139.126 99.456 139.946 101.425 141.431C101.312 143.672 100.918 144.785 98.5027 146.02V151.026C98.5027 155.616 90.5711 155.199 90.5711 155.199C86.3966 155.199 83.4745 151.026 83.4745 151.026C83.0237 149.203 82.0278 148.304 79.3 146.854V138.928H85.9792C85.3427 140.411 85.3622 141.614 85.5617 143.934C87.3178 147.935 88.5478 148.245 90.9886 146.854C90.7532 144.265 91.0342 142.898 92.2409 140.596Z"
            fill="url(#paint4_linear_78_256)" stroke="#B18944" stroke-width="0.8349" />
          <path d="M79.3 134.332H75.543V146.855H79.3V134.332Z" fill="#E8D5AB" stroke="#B18944" stroke-width="0.8349" />
          <g filter="url(#filter0_d_78_256)">
            <path
              d="M64.6891 105.11L68.0287 108.032C63.752 113.82 63.5803 118.003 65.524 126.4C62.2243 122.269 59.6797 123.478 59.6797 125.983C59.6797 128.487 62.7435 131.086 70.116 133.914L75.5428 134.332V138.924H69.2811C67.9352 136.421 66.2115 136.426 63.4368 136.001L55.9227 137.671C54.2089 128.125 51.0248 127.17 43.8166 128.487V121.391C42.0609 118.589 40.8117 117.04 38.3898 114.294C36.1055 108.212 36.1277 105.284 39.6421 101.353C42.317 98.4683 42.8202 96.4007 51.7482 96.3437C56.0965 96.3789 58.715 97.2737 64.6891 105.11Z"
              fill="url(#paint5_linear_78_256)" stroke="#8A6D38" stroke-width="0.8349" />
            <path
              d="M62.5716 106.703C62.5716 106.703 66.2164 107.945 65.4065 109.6C64.5965 111.256 53.3861 107.997 49.2073 109.6C49.2073 109.6 42.7276 112.083 40.7027 113.325C38.6778 114.567 39.8135 106.888 41.9176 102.978C44.26 100.969 45.8327 100.035 50.4222 99.6671C54.6064 98.3802 57.2993 100.05 62.5716 106.703Z"
              fill="url(#paint6_linear_78_256)" />
            <path
              d="M90.2466 105.11L86.9068 108.032C91.1838 113.82 91.3555 118.003 89.4116 126.4C92.7116 122.269 95.2564 123.478 95.2564 125.983C95.2564 128.487 92.1924 131.086 84.8193 133.914L79.392 134.332V138.924H85.6543C87.0003 136.421 88.7241 136.426 91.4991 136.001L99.0138 137.671C100.728 128.125 103.912 127.17 111.121 128.487V121.391C112.877 118.589 114.126 117.04 116.548 114.294C118.833 108.212 118.81 105.284 115.296 101.353C112.62 98.4683 112.117 96.4007 103.189 96.3437C98.8399 96.3789 96.2212 97.2737 90.2466 105.11Z"
              fill="url(#paint7_linear_78_256)" stroke="#8A6D38" stroke-width="0.8349" />
            <path
              d="M92.3642 106.703C92.3642 106.703 88.719 107.945 89.5291 109.6C90.3391 111.256 101.55 107.997 105.73 109.6C105.73 109.6 112.21 112.083 114.235 113.325C116.26 114.567 115.124 106.888 113.02 102.978C110.677 100.969 109.104 100.035 104.515 99.6671C100.33 98.3802 97.6369 100.05 92.3642 106.703Z"
              fill="url(#paint8_linear_78_256)" />
          </g>
          <g filter="url(#filter1_d_78_256)">
            <path
              d="M36.8864 132.915V136.749C39.0572 142.334 41.8945 145.66 51 152.088V153.792C49.3874 156.203 48.5942 157.487 47.8636 159.331C43.9057 183.625 42.8894 196.811 44.75 219C44.75 219 42.2457 216.514 40.3674 216.514C38.4891 216.514 36.8864 219 36.8864 219C36.4194 214.25 31.3695 154.588 28 150.384V135.471L30.6136 132.915C33.012 131.833 34.3727 131.565 36.8864 132.915Z"
              fill="url(#paint9_linear_78_256)" shape-rendering="crispEdges" />
            <path
              d="M36.8864 132.915V136.749C39.0572 142.334 41.8945 145.66 51 152.088V153.792C49.3874 156.203 48.5942 157.487 47.8636 159.331C43.9057 183.625 42.8894 196.811 44.75 219C44.75 219 42.2457 216.514 40.3674 216.514C38.4891 216.514 36.8864 219 36.8864 219C36.4194 214.25 31.3695 154.588 28 150.384V135.471L30.6136 132.915C33.012 131.833 34.3727 131.565 36.8864 132.915Z"
              stroke="#B18944" stroke-opacity="0.89" stroke-width="0.8349" shape-rendering="crispEdges" />
          </g>
          <path
            d="M49.4084 321.711L48.8858 317.635C46.6299 318.052 45.3806 317.626 43.1365 316.005L42.6136 318.45C41.4387 321.506 41.4189 323.061 41.5683 325.787L35.8194 339.645C34.7498 341.52 34.7042 342.26 35.8194 342.905L42.0914 329.863L36.3421 343.72C36.4656 345.527 36.5795 346.392 37.91 344.536L43.1365 330.678L41.5685 337.199L38.4412 345.558C38.4815 346.582 38.5091 347.213 40.0006 346.981L43.6591 338.014L44.1818 331.493C44.6647 329.596 45.0513 328.99 46.2724 329.863L44.7044 338.014L42.0914 346.981C41.5687 348.611 43.6593 347.796 43.6593 347.796L46.2725 339.645L47.3178 333.938C47.7025 330.517 48.0467 329.122 48.8858 327.417C50.3675 325.2 50.1879 323.948 49.4084 321.711Z"
            fill="#FCC36E" />
          <path
            d="M38.4326 345.351C38.4358 345.421 38.4385 345.49 38.4412 345.558M38.4412 345.558C38.4815 346.582 38.5091 347.213 40.0006 346.981L43.6591 338.014L44.1818 331.493C44.6647 329.596 45.0513 328.99 46.2724 329.863L44.7044 338.014L42.0914 346.981C41.5687 348.611 43.6593 347.796 43.6593 347.796L46.2725 339.645L47.3178 333.938C47.7025 330.517 48.0467 329.122 48.8858 327.417C50.3675 325.2 50.1879 323.948 49.4084 321.711L48.8858 317.635C46.6299 318.052 45.3806 317.626 43.1365 316.005L42.6136 318.45C41.4387 321.506 41.4189 323.061 41.5683 325.787L35.8194 339.645C34.7498 341.52 34.7042 342.26 35.8194 342.905L42.0914 329.863L36.3421 343.72C36.4656 345.527 36.5795 346.392 37.91 344.536L43.1365 330.678L41.5685 337.199L38.4412 345.558Z"
            stroke="black" />
          <path
            d="M43.6586 311.114L42.6133 314.374C42.493 315.625 42.7833 316.166 43.6586 316.82C43.6586 316.82 47.3172 318.45 48.3625 317.635C49.4078 316.82 48.3625 314.374 48.3625 314.374C47.638 312.457 46.6382 311.715 43.6586 311.114Z"
            fill="#EBAA53" stroke="black" />
          <path
            d="M35.8196 227.152C35.3545 223.952 35.9038 222.65 37.3875 220.63L40.0006 228.782C40.382 243.07 41.0257 250.458 42.6139 263.019L43.6592 311.114C43.2845 311.598 43.1365 313.559 42.0912 314.374C41.0459 315.19 40.0006 267.91 40.0006 267.91C39.8876 254.499 39.0431 247.836 37.3875 236.118C36.6215 234.239 36.3353 231.71 35.8267 227.215L35.8196 227.152Z"
            fill="url(#paint10_linear_78_256)" stroke="#B18944" />
          <path
            d="M48.3628 318.45C46.5067 318.949 45.4871 318.79 43.6589 317.635C41.7258 319.748 41.5821 321.835 41.5684 325.787C44.8103 323.235 46.2986 323.516 48.3628 327.417C49.4674 325.297 49.4589 324.255 48.8854 322.526L48.3628 318.45Z"
            fill="#FEB548" stroke="black" />
          <path
            d="M41.5685 219C40.1887 220.615 38.4326 219 37.9099 219.815C37.3873 220.63 40.0005 229.597 40.0005 229.597C42.8353 249.506 43.8242 258.436 43.6591 267.095V311.114C46.17 311.361 47.2027 312.095 48.3629 314.374C49.2947 311.366 49.0732 309.03 48.3629 304.592C47.1918 296.258 46.7828 290.283 46.2723 278.507L45.7496 229.597C47.1366 226.588 47.0411 225.007 46.2723 222.261C44.8786 221.174 41.9866 219 41.5685 219Z"
            fill="url(#paint11_linear_78_256)" stroke="#B18944" />
          <path
            d="M37.1663 220.083C36.5135 218.333 37.8194 216 40.4305 216C43.0417 216 44.9997 217.75 45 218.917C45.0003 220.083 44.9997 223 41.7361 223C38.4725 223 37.8191 221.833 37.1663 220.083Z"
            fill="#D8A331" stroke="black" stroke-opacity="0.72" />
          <g filter="url(#filter2_d_78_256)">
            <path
              d="M118.114 132.915V136.749C115.943 142.334 113.105 145.66 104 152.088V153.792C105.613 156.203 106.406 157.487 107.136 159.331C111.094 183.625 112.111 196.811 110.25 219C110.25 219 112.754 216.514 114.633 216.514C116.511 216.514 118.114 219 118.114 219C118.581 214.25 123.63 154.588 127 150.384V135.471L124.386 132.915C121.988 131.833 120.627 131.565 118.114 132.915Z"
              fill="url(#paint12_linear_78_256)" shape-rendering="crispEdges" />
            <path
              d="M118.114 132.915V136.749C115.943 142.334 113.105 145.66 104 152.088V153.792C105.613 156.203 106.406 157.487 107.136 159.331C111.094 183.625 112.111 196.811 110.25 219C110.25 219 112.754 216.514 114.633 216.514C116.511 216.514 118.114 219 118.114 219C118.581 214.25 123.63 154.588 127 150.384V135.471L124.386 132.915C121.988 131.833 120.627 131.565 118.114 132.915Z"
              stroke="#B18944" stroke-opacity="0.89" stroke-width="0.8349" shape-rendering="crispEdges" />
          </g>
          <path
            d="M105.591 321.711L106.114 317.635C108.37 318.052 109.619 317.626 111.863 316.005L112.386 318.45C113.561 321.506 113.581 323.061 113.431 325.787L119.18 339.645C120.25 341.52 120.295 342.26 119.18 342.905L112.908 329.863L118.657 343.72C118.534 345.527 118.42 346.392 117.09 344.536L111.863 330.678L113.431 337.199L116.558 345.558C116.518 346.582 116.49 347.213 114.999 346.981L111.34 338.014L110.818 331.493C110.335 329.596 109.948 328.99 108.727 329.863L110.295 338.014L112.908 346.981C113.431 348.611 111.34 347.796 111.34 347.796L108.727 339.645L107.682 333.938C107.297 330.517 106.953 329.122 106.114 327.417C104.632 325.2 104.812 323.948 105.591 321.711Z"
            fill="#FCC36E" />
          <path
            d="M116.567 345.351C116.564 345.421 116.561 345.49 116.558 345.558M116.558 345.558C116.518 346.582 116.49 347.213 114.999 346.981L111.34 338.014L110.818 331.493C110.335 329.596 109.948 328.99 108.727 329.863L110.295 338.014L112.908 346.981C113.431 348.611 111.34 347.796 111.34 347.796L108.727 339.645L107.682 333.938C107.297 330.517 106.953 329.122 106.114 327.417C104.632 325.2 104.812 323.948 105.591 321.711L106.114 317.635C108.37 318.052 109.619 317.626 111.863 316.005L112.386 318.45C113.561 321.506 113.581 323.061 113.431 325.787L119.18 339.645C120.25 341.52 120.295 342.26 119.18 342.905L112.908 329.863L118.657 343.72C118.534 345.527 118.42 346.392 117.09 344.536L111.863 330.678L113.431 337.199L116.558 345.558Z"
            stroke="black" />
          <path
            d="M111.341 311.114L112.387 314.374C112.507 315.625 112.217 316.166 111.341 316.82C111.341 316.82 107.683 318.45 106.638 317.635C105.592 316.82 106.638 314.374 106.638 314.374C107.362 312.457 108.362 311.715 111.341 311.114Z"
            fill="#EBAA53" stroke="black" />
          <path
            d="M119.181 227.152C119.646 223.952 119.097 222.65 117.613 220.63L115 228.782C114.618 243.07 113.975 250.458 112.387 263.019L111.341 311.114C111.716 311.598 111.864 313.559 112.909 314.374C113.955 315.19 115 267.91 115 267.91C115.113 254.499 115.957 247.836 117.613 236.118C118.379 234.239 118.665 231.71 119.174 227.215L119.181 227.152Z"
            fill="url(#paint13_linear_78_256)" stroke="#B18944" />
          <path
            d="M106.637 318.45C108.493 318.949 109.513 318.79 111.341 317.635C113.274 319.748 113.418 321.835 113.432 325.787C110.19 323.235 108.701 323.516 106.637 327.417C105.533 325.297 105.541 324.255 106.115 322.526L106.637 318.45Z"
            fill="#FEB548" stroke="black" />
          <path
            d="M113.432 219C114.811 220.615 116.567 219 117.09 219.815C117.613 220.63 114.999 229.597 114.999 229.597C112.165 249.506 111.176 258.436 111.341 267.095V311.114C108.83 311.361 107.797 312.095 106.637 314.374C105.705 311.366 105.927 309.03 106.637 304.592C107.808 296.258 108.217 290.283 108.728 278.507L109.25 229.597C107.863 226.588 107.959 225.007 108.728 222.261C110.121 221.174 113.013 219 113.432 219Z"
            fill="url(#paint14_linear_78_256)" stroke="#B18944" />
          <path
            d="M117.833 220.083C118.486 218.333 117.18 216 114.569 216C111.958 216 110 217.75 110 218.917C109.999 220.083 110 223 113.263 223C116.527 223 117.18 221.833 117.833 220.083Z"
            fill="#D8A331" stroke="black" stroke-opacity="0.72" />
          <path
            d="M81.1605 14.106C78.5974 14.8272 77.1836 14.8383 74.4813 14.106V16.6107C76.8602 17.7954 78.3128 17.8671 81.1605 16.6107V14.106Z"
            fill="#EDC16B" />
          <path
            d="M81.1605 18.2805C78.5974 19.0017 77.1836 19.0128 74.4813 18.2805V20.7852C76.8602 21.9699 78.3128 22.0416 81.1605 20.7852V18.2805Z"
            fill="#EDC16B" />
          <path
            d="M81.1605 22.455C78.5974 23.1762 77.1836 23.1873 74.4813 22.455V24.9597C76.8602 26.1444 78.3128 26.2161 81.1605 24.9597V22.455Z"
            fill="#EDC16B" />
          <path
            d="M81.1605 27.047C78.5974 27.7681 77.1836 27.7793 74.4813 27.047V29.5517C76.8602 30.7364 78.3128 30.8081 81.1605 29.5517V27.047Z"
            fill="#EDC16B" />
          <path
            d="M81.1605 31.2215C78.5974 31.9426 77.1836 31.9538 74.4813 31.2215V33.7262C76.8602 34.9109 78.3128 34.9826 81.1605 33.7262V31.2215Z"
            fill="#EDC16B" />
          <path
            d="M81.1605 35.396C78.5974 36.1171 77.1836 36.1283 74.4813 35.396V37.9007C76.8602 39.0854 78.3128 39.1571 81.1605 37.9007V35.396Z"
            fill="#EDC16B" />
          <path
            d="M81.1605 39.5705C78.5974 40.2916 77.1836 40.3028 74.4813 39.5705V42.0752C76.8602 43.2599 78.3128 43.3316 81.1605 42.0752V39.5705Z"
            fill="#EDC16B" />
          <path
            d="M81.1605 43.745C78.5974 44.4661 77.1836 44.4773 74.4813 43.745V46.2497C76.8602 47.4344 78.3128 47.5061 81.1605 46.2497V43.745Z"
            fill="#EDC16B" />
          <path
            d="M81.1605 47.502C78.5974 48.2232 77.1836 48.2343 74.4813 47.502V50.0067C76.8602 51.1914 78.3128 51.2631 81.1605 50.0067V47.502Z"
            fill="#EDC16B" />
          <path
            d="M81.1605 51.6765C78.5974 52.3977 77.1836 52.4088 74.4813 51.6765V54.1812C76.8602 55.3659 78.3128 55.4376 81.1605 54.1812V51.6765Z"
            fill="#EDC16B" />
          <path
            d="M81.1605 55.851C78.5974 56.5722 77.1836 56.5833 74.4813 55.851V58.3557C76.8602 59.5404 78.3128 59.6121 81.1605 58.3557V55.851Z"
            fill="#EDC16B" />
          <path
            d="M81.1605 60.0255C78.5974 60.7467 77.1836 60.7578 74.4813 60.0255V62.5302C76.8602 63.7149 78.3128 63.7866 81.1605 62.5302V60.0255Z"
            fill="#EDC16B" />
          <path
            d="M81.1605 64.2C78.5974 64.9212 77.1836 64.9323 74.4813 64.2V66.7047C76.8602 67.8894 78.3128 67.9611 81.1605 66.7047V64.2Z"
            fill="#EDC16B" />
          <path
            d="M81.1605 67.5396C78.5974 68.2608 77.1836 68.2719 74.4813 67.5396V70.0443C76.8602 71.229 78.3128 71.3007 81.1605 70.0443V67.5396Z"
            fill="#EDC16B" />
          <path
            d="M81.1605 71.7141C78.5974 72.4353 77.1836 72.4464 74.4813 71.7141V74.2188C76.8602 75.4035 78.3128 75.4752 81.1605 74.2188V71.7141Z"
            fill="#EDC16B" />
          <path
            d="M81.1605 75.8886C78.5974 76.6098 77.1836 76.6209 74.4813 75.8886V78.3933C76.8602 79.578 78.3128 79.6497 81.1605 78.3933V75.8886Z"
            fill="#EDC16B" />
          <path
            d="M81.1605 80.0631C78.5974 80.7843 77.1836 80.7954 74.4813 80.0631V82.5678C76.8602 83.7525 78.3128 83.8242 81.1605 82.5678V80.0631Z"
            fill="#EDC16B" />
          <path
            d="M81.1605 84.2376C78.5974 84.9588 77.1836 84.9699 74.4813 84.2376V86.7423C76.8602 87.927 78.3128 87.9987 81.1605 86.7423V84.2376Z"
            fill="#EDC16B" />
          <path
            d="M81.1605 88.4121C78.5974 89.1333 77.1836 89.1444 74.4813 88.4121V90.9168C76.8602 92.1015 78.3128 92.1732 81.1605 90.9168V88.4121Z"
            fill="#EDC16B" />
          <path
            d="M81.1605 92.5866C78.5974 93.3078 77.1836 93.3189 74.4813 92.5866V95.0913C76.8602 96.276 78.3128 96.3477 81.1605 95.0913V92.5866Z"
            fill="#EDC16B" />
          <path
            d="M81.1605 96.7611C78.5974 97.4823 77.1836 97.4934 74.4813 96.7611V99.2658C76.8602 100.451 78.3128 100.522 81.1605 99.2658V96.7611Z"
            fill="#EDC16B" />
          <path
            d="M81.1605 100.936C78.5974 101.657 77.1836 101.668 74.4813 100.936V103.44C76.8602 104.625 78.3128 104.697 81.1605 103.44V100.936Z"
            fill="#EDC16B" />
          <path
            d="M81.1605 105.11C78.5974 105.831 77.1836 105.842 74.4813 105.11V107.615C76.8602 108.8 78.3128 108.871 81.1605 107.615V105.11Z"
            fill="#EDC16B" />
          <path
            d="M81.1605 109.285C78.5974 110.006 77.1836 110.017 74.4813 109.285V111.789C76.8602 112.974 78.3128 113.046 81.1605 111.789V109.285Z"
            fill="#EDC16B" />
          <path
            d="M81.1605 14.106C78.5974 14.8272 77.1836 14.8383 74.4813 14.106V16.6107C76.8602 17.7954 78.3128 17.8671 81.1605 16.6107V14.106Z"
            stroke="black" stroke-opacity="0.5" stroke-width="0.8349" />
          <path
            d="M81.1605 18.2805C78.5974 19.0017 77.1836 19.0128 74.4813 18.2805V20.7852C76.8602 21.9699 78.3128 22.0416 81.1605 20.7852V18.2805Z"
            stroke="black" stroke-opacity="0.5" stroke-width="0.8349" />
          <path
            d="M81.1605 22.455C78.5974 23.1762 77.1836 23.1873 74.4813 22.455V24.9597C76.8602 26.1444 78.3128 26.2161 81.1605 24.9597V22.455Z"
            stroke="black" stroke-opacity="0.5" stroke-width="0.8349" />
          <path
            d="M81.1605 27.047C78.5974 27.7681 77.1836 27.7793 74.4813 27.047V29.5517C76.8602 30.7364 78.3128 30.8081 81.1605 29.5517V27.047Z"
            stroke="black" stroke-opacity="0.5" stroke-width="0.8349" />
          <path
            d="M81.1605 31.2215C78.5974 31.9426 77.1836 31.9538 74.4813 31.2215V33.7262C76.8602 34.9109 78.3128 34.9826 81.1605 33.7262V31.2215Z"
            stroke="black" stroke-opacity="0.5" stroke-width="0.8349" />
          <path
            d="M81.1605 35.396C78.5974 36.1171 77.1836 36.1283 74.4813 35.396V37.9007C76.8602 39.0854 78.3128 39.1571 81.1605 37.9007V35.396Z"
            stroke="black" stroke-opacity="0.5" stroke-width="0.8349" />
          <path
            d="M81.1605 39.5705C78.5974 40.2916 77.1836 40.3028 74.4813 39.5705V42.0752C76.8602 43.2599 78.3128 43.3316 81.1605 42.0752V39.5705Z"
            stroke="black" stroke-opacity="0.5" stroke-width="0.8349" />
          <path
            d="M81.1605 43.745C78.5974 44.4661 77.1836 44.4773 74.4813 43.745V46.2497C76.8602 47.4344 78.3128 47.5061 81.1605 46.2497V43.745Z"
            stroke="black" stroke-opacity="0.5" stroke-width="0.8349" />
          <path
            d="M81.1605 47.502C78.5974 48.2232 77.1836 48.2343 74.4813 47.502V50.0067C76.8602 51.1914 78.3128 51.2631 81.1605 50.0067V47.502Z"
            stroke="black" stroke-opacity="0.5" stroke-width="0.8349" />
          <path
            d="M81.1605 51.6765C78.5974 52.3977 77.1836 52.4088 74.4813 51.6765V54.1812C76.8602 55.3659 78.3128 55.4376 81.1605 54.1812V51.6765Z"
            stroke="black" stroke-opacity="0.5" stroke-width="0.8349" />
          <path
            d="M81.1605 55.851C78.5974 56.5722 77.1836 56.5833 74.4813 55.851V58.3557C76.8602 59.5404 78.3128 59.6121 81.1605 58.3557V55.851Z"
            stroke="black" stroke-opacity="0.5" stroke-width="0.8349" />
          <path
            d="M81.1605 60.0255C78.5974 60.7467 77.1836 60.7578 74.4813 60.0255V62.5302C76.8602 63.7149 78.3128 63.7866 81.1605 62.5302V60.0255Z"
            stroke="black" stroke-opacity="0.5" stroke-width="0.8349" />
          <path
            d="M81.1605 64.2C78.5974 64.9212 77.1836 64.9323 74.4813 64.2V66.7047C76.8602 67.8894 78.3128 67.9611 81.1605 66.7047V64.2Z"
            stroke="black" stroke-opacity="0.5" stroke-width="0.8349" />
          <path
            d="M81.1605 67.5396C78.5974 68.2608 77.1836 68.2719 74.4813 67.5396V70.0443C76.8602 71.229 78.3128 71.3007 81.1605 70.0443V67.5396Z"
            stroke="black" stroke-opacity="0.5" stroke-width="0.8349" />
          <path
            d="M81.1605 71.7141C78.5974 72.4353 77.1836 72.4464 74.4813 71.7141V74.2188C76.8602 75.4035 78.3128 75.4752 81.1605 74.2188V71.7141Z"
            stroke="black" stroke-opacity="0.5" stroke-width="0.8349" />
          <path
            d="M81.1605 75.8886C78.5974 76.6098 77.1836 76.6209 74.4813 75.8886V78.3933C76.8602 79.578 78.3128 79.6497 81.1605 78.3933V75.8886Z"
            stroke="black" stroke-opacity="0.5" stroke-width="0.8349" />
          <path
            d="M81.1605 80.0631C78.5974 80.7843 77.1836 80.7954 74.4813 80.0631V82.5678C76.8602 83.7525 78.3128 83.8242 81.1605 82.5678V80.0631Z"
            stroke="black" stroke-opacity="0.5" stroke-width="0.8349" />
          <path
            d="M81.1605 84.2376C78.5974 84.9588 77.1836 84.9699 74.4813 84.2376V86.7423C76.8602 87.927 78.3128 87.9987 81.1605 86.7423V84.2376Z"
            stroke="black" stroke-opacity="0.5" stroke-width="0.8349" />
          <path
            d="M81.1605 88.4121C78.5974 89.1333 77.1836 89.1444 74.4813 88.4121V90.9168C76.8602 92.1015 78.3128 92.1732 81.1605 90.9168V88.4121Z"
            stroke="black" stroke-opacity="0.5" stroke-width="0.8349" />
          <path
            d="M81.1605 92.5866C78.5974 93.3078 77.1836 93.3189 74.4813 92.5866V95.0913C76.8602 96.276 78.3128 96.3477 81.1605 95.0913V92.5866Z"
            stroke="black" stroke-opacity="0.5" stroke-width="0.8349" />
          <path
            d="M81.1605 96.7611C78.5974 97.4823 77.1836 97.4934 74.4813 96.7611V99.2658C76.8602 100.451 78.3128 100.522 81.1605 99.2658V96.7611Z"
            stroke="black" stroke-opacity="0.5" stroke-width="0.8349" />
          <path
            d="M81.1605 100.936C78.5974 101.657 77.1836 101.668 74.4813 100.936V103.44C76.8602 104.625 78.3128 104.697 81.1605 103.44V100.936Z"
            stroke="black" stroke-opacity="0.5" stroke-width="0.8349" />
          <path
            d="M81.1605 105.11C78.5974 105.831 77.1836 105.842 74.4813 105.11V107.615C76.8602 108.8 78.3128 108.871 81.1605 107.615V105.11Z"
            stroke="black" stroke-opacity="0.5" stroke-width="0.8349" />
          <path
            d="M81.1605 109.285C78.5974 110.006 77.1836 110.017 74.4813 109.285V111.789C76.8602 112.974 78.3128 113.046 81.1605 111.789V109.285Z"
            stroke="black" stroke-opacity="0.5" stroke-width="0.8349" />
          <path
            d="M109.547 86.7424C112.203 82.6046 112.273 80.4959 112.469 76.7236C110.399 80.3177 107.877 83.4028 103.703 84.2377C99.5284 85.0726 97.7239 83.4243 94.1016 80.8981L95.7714 84.6551C102.177 89.8725 105.496 91.6298 109.547 86.7424Z"
            fill="#CB9A4D" stroke="#856646" stroke-width="0.8349" />
          <path
            d="M46.0949 86.8681C43.4391 82.8509 43.3694 80.8035 43.1727 77.141C45.2432 80.6305 47.7647 83.6258 51.9392 84.4364C56.1137 85.247 57.9182 83.6467 61.5405 81.194L59.8707 84.8417C53.4647 89.9071 50.1464 91.6134 46.0949 86.8681Z"
            fill="#CB9A4D" stroke="#856646" stroke-width="0.8349" />
          <path
            d="M108.712 91.7177C110.363 89.1457 110.406 87.8349 110.529 85.49C109.242 87.7241 107.674 89.6418 105.079 90.1608C102.485 90.6797 98.2763 87.1598 97.024 87.5773C95.7716 87.9947 98.2763 90.9169 98.2763 90.9169C102.258 94.16 106.194 94.7558 108.712 91.7177Z"
            fill="#CB9A4D" stroke="#856646" stroke-width="0.518974" />
          <path
            d="M46.6597 91.8219C45.0085 89.2068 44.9651 87.8741 44.8428 85.49C46.1302 87.7615 47.698 89.7112 50.2936 90.2389C52.8892 90.7665 57.0987 87.1877 58.3514 87.6122C59.6041 88.0366 57.0987 91.0076 57.0987 91.0076C53.1155 94.305 49.1789 94.9107 46.6597 91.8219Z"
            fill="#CB9A4D" stroke="#856646" stroke-width="0.518974" />
          <g filter="url(#filter3_d_78_256)">
            <path
              d="M112.472 63.3652C112.89 60.8605 112.526 58.148 111.22 55.4336L109.55 56.686C111.164 62.4112 110.116 65.2587 99.9489 68.792C95.6936 68.1504 95.7748 64.2001 95.7748 64.2001L81.5815 54.1813V58.3558L92.0174 70.8793C92.0174 70.8793 97.8617 72.9665 101.619 72.1316C105.376 71.2967 112.055 65.8699 112.472 63.3652Z"
              fill="#CB9A4D" />
            <path
              d="M112.472 63.3652C112.89 60.8605 112.526 58.148 111.22 55.4336L109.55 56.686C111.164 62.4112 110.116 65.2587 99.9489 68.792C95.6936 68.1504 95.7748 64.2001 95.7748 64.2001L81.5815 54.1813V58.3558L92.0174 70.8793C92.0174 70.8793 97.8617 72.9665 101.619 72.1316C105.376 71.2967 112.055 65.8699 112.472 63.3652Z"
              stroke="#856646" stroke-width="0.8349" />
          </g>
          <g filter="url(#filter4_d_78_256)">
            <path
              d="M43.3375 63.0592C42.92 60.5241 43.2843 57.7787 44.5899 55.0313L46.2599 56.2989C44.6462 62.0936 45.6942 64.9757 55.8622 68.5519C60.118 67.9025 60.0367 63.9042 60.0367 63.9042L74.2314 53.7638V57.989L63.7946 70.6645C63.7946 70.6645 57.9497 72.7771 54.1922 71.9321C50.4348 71.087 43.7549 65.5943 43.3375 63.0592Z"
              fill="#CB9A4D" />
            <path
              d="M43.3375 63.0592C42.92 60.5241 43.2843 57.7787 44.5899 55.0313L46.2599 56.2989C44.6462 62.0936 45.6942 64.9757 55.8622 68.5519C60.118 67.9025 60.0367 63.9042 60.0367 63.9042L74.2314 53.7638V57.989L63.7946 70.6645C63.7946 70.6645 57.9497 72.7771 54.1922 71.9321C50.4348 71.087 43.7549 65.5943 43.3375 63.0592Z"
              stroke="#856646" stroke-width="0.8349" />
          </g>
          <g filter="url(#filter5_d_78_256)">
            <path
              d="M110.8 54.1812C111.217 51.6765 110.853 48.9641 109.547 46.2497L107.877 47.502C109.491 53.2272 108.443 56.0747 98.2761 59.6081C94.0208 58.9665 92.848 57.6911 92.4318 54.1812L81.5781 53.7638C85.7523 56.7924 88.6748 58.7732 91.5969 60.8604C94.5191 62.9477 96.1889 63.7826 99.9459 62.9477C103.703 62.1128 110.382 56.6859 110.8 54.1812Z"
              fill="#CB9A4D" />
            <path
              d="M110.8 54.1812C111.217 51.6765 110.853 48.9641 109.547 46.2497L107.877 47.502C109.491 53.2272 108.443 56.0747 98.2761 59.6081C94.0208 58.9665 92.848 57.6911 92.4318 54.1812L81.5781 53.7638C85.7523 56.7924 88.6748 58.7732 91.5969 60.8604C94.5191 62.9477 96.1889 63.7826 99.9459 62.9477C103.703 62.1128 110.382 56.6859 110.8 54.1812Z"
              stroke="#856646" stroke-width="0.8349" />
          </g>
          <g filter="url(#filter6_d_78_256)">
            <path
              d="M45.0073 54.0321C44.5898 51.5745 44.9541 48.913 46.2597 46.2497L47.9297 47.4785C46.316 53.0961 47.364 55.89 57.5319 59.357C61.7876 58.7274 62.9605 57.476 63.3767 54.0321L74.2314 53.6225C70.0569 56.5942 67.1341 58.5378 64.2117 60.5858C61.2893 62.6338 59.6194 63.453 55.862 62.6338C52.1046 61.8146 45.4247 56.4897 45.0073 54.0321Z"
              fill="#CB9A4D" />
            <path
              d="M45.0073 54.0321C44.5898 51.5745 44.9541 48.913 46.2597 46.2497L47.9297 47.4785C46.316 53.0961 47.364 55.89 57.5319 59.357C61.7876 58.7274 62.9605 57.476 63.3767 54.0321L74.2314 53.6225C70.0569 56.5942 67.1341 58.5378 64.2117 60.5858C61.2893 62.6338 59.6194 63.453 55.862 62.6338C52.1046 61.8146 45.4247 56.4897 45.0073 54.0321Z"
              stroke="#856646" stroke-width="0.8349" />
          </g>
          <g filter="url(#filter7_d_78_256)">
            <path
              d="M114.139 72.9665C114.556 70.4618 113.358 67.3319 112.052 64.6175L111.217 66.2873C112.83 72.0125 112.618 75.6949 102.451 79.2282C98.1953 78.5866 98.2762 76.3061 98.2762 76.3061L81.9956 65.4524V68.3745C87.4566 71.566 90.6086 73.1992 93.6838 80.4806C93.6838 80.4806 99.946 84.6551 103.703 83.8202C107.46 82.9853 113.721 75.4712 114.139 72.9665Z"
              fill="#CB9A4D" />
            <path
              d="M114.139 72.9665C114.556 70.4618 113.358 67.3319 112.052 64.6175L111.217 66.2873C112.83 72.0125 112.618 75.6949 102.451 79.2282C98.1953 78.5866 98.2762 76.3061 98.2762 76.3061L81.9956 65.4524V68.3745C87.4566 71.566 90.6086 73.1992 93.6838 80.4806C93.6838 80.4806 99.946 84.6551 103.703 83.8202C107.46 82.9853 113.721 75.4712 114.139 72.9665Z"
              stroke="#856646" stroke-width="0.8349" />
          </g>
          <g filter="url(#filter8_d_78_256)">
            <path
              d="M41.5878 72.9188C41.1703 70.4284 42.3691 67.3164 43.6746 64.6175L44.5099 66.2777C42.8964 71.9702 43.109 75.6316 53.2758 79.1447C57.531 78.5068 57.4502 76.2393 57.4502 76.2393L73.7305 65.4476V68.3531C68.2695 71.5263 65.1177 73.1502 62.0425 80.3899C62.0425 80.3899 55.7804 84.5406 52.0234 83.7104C48.2665 82.8803 42.0052 75.4092 41.5878 72.9188Z"
              fill="#CB9A4D" />
            <path
              d="M41.5878 72.9188C41.1703 70.4284 42.3691 67.3164 43.6746 64.6175L44.5099 66.2777C42.8964 71.9702 43.109 75.6316 53.2758 79.1447C57.531 78.5068 57.4502 76.2393 57.4502 76.2393L73.7305 65.4476V68.3531C68.2695 71.5263 65.1177 73.1502 62.0425 80.3899C62.0425 80.3899 55.7804 84.5406 52.0234 83.7104C48.2665 82.8803 42.0052 75.4092 41.5878 72.9188Z"
              stroke="#856646" stroke-width="0.8349" />
          </g>
          <path d="M84.0823 9.5141L81.5776 9.93155V11.6013L88.6743 10.349L84.0823 9.5141Z" fill="#CB9A4D" />
          <path
            d="M83.6649 8.6792C83.1019 9.19714 82.6187 9.36865 81.5776 9.5141V9.93155L84.0823 9.5141L88.6743 10.349L81.5776 11.6013V12.4362L84.0823 12.0188C84.0823 12.0188 87.8394 11.6013 89.0917 11.1839C90.3441 10.7664 89.4168 9.98261 88.6743 9.5141L83.6649 8.6792Z"
            fill="#B08747" />
          <path d="M72.1767 9.5141L74.6821 9.93155V11.6013L67.5834 10.349L72.1767 9.5141Z" fill="#CB9A4D" />
          <path
            d="M72.5943 8.6792C73.1574 9.19714 73.6408 9.36865 74.6821 9.5141V9.93155L72.1767 9.5141L67.5834 10.349L74.6821 11.6013V12.4362L72.1767 12.0188C72.1767 12.0188 68.4186 11.6013 67.1659 11.1839C65.9131 10.7664 66.8407 9.98261 67.5834 9.5141L72.5943 8.6792Z"
            fill="#B08747" />
          <path
            d="M99.5285 17.8631C99.1111 17.0282 96.4653 14.2058 94.5191 13.2712L98.2762 18.2806C98.2762 18.2806 99.1111 20.7853 98.6936 21.6202C98.2762 22.4551 93.6842 24.5423 91.597 25.3772C89.5097 26.2121 81.9956 27.4645 81.9956 27.4645V28.7168L91.597 26.6296C91.597 26.6296 98.6936 23.7074 99.5285 22.4551C100.363 21.2027 99.946 18.698 99.5285 17.8631Z"
            fill="#B08747" />
          <g filter="url(#filter9_d_78_256)">
            <path
              d="M99.1111 22.0376C99.3573 18.5412 96.9337 16.6544 94.5191 13.2712C95.8987 16.1708 96.9174 17.9498 96.1889 19.5329C95.2653 21.0394 94.5847 21.6149 93.2668 22.4551C89.555 24.4623 87.1175 25.0201 81.9956 24.9598V27.4645C88.521 26.505 92.9377 25.3886 99.1111 22.0376Z"
              fill="#CB9A4D" />
          </g>
          <path
            d="M91.3961 14.5903C91.1623 14.1228 90.5991 13.7945 89.5092 13.2712L90.6947 14.8241C90.6947 14.8241 91.1623 16.2267 90.9285 16.6943C90.6947 17.1618 88.1233 18.3307 86.9544 18.7982C85.7855 19.2658 81.5776 19.9671 81.5776 19.9671V20.6684C85.1497 19.9564 88.2568 19.9671 89.5092 19.5329C90.7615 19.0988 91.5463 18.147 92.0139 17.4457C92.4769 16.7512 91.6463 15.0907 91.4031 14.6044L91.3961 14.5903Z"
            fill="#B08747" />
          <g filter="url(#filter10_d_78_256)">
            <path
              d="M91.1623 16.9281C91.6533 15.2916 89.5092 13.2712 89.5092 13.2712C89.5092 13.2712 90.3775 14.4401 89.5259 15.5254C88.6743 16.6108 88.6276 16.6913 87.8895 17.1618C85.8109 18.2859 84.4459 18.5982 81.5776 18.5645V19.9671C85.2319 19.4298 90.6713 18.5645 91.1623 16.9281Z"
              fill="#CB9A4D" />
          </g>
          <path
            d="M92.8488 9.93157C94.1011 9.49742 92.0233 7.84433 92.0233 7.84433C91.0663 6.86401 90.5095 6.54462 89.5092 6.1745L87.8394 5.3396L83.6649 4.5047L81.5776 5.3396C84.8811 5.22875 87.0045 5.75705 88.6743 6.59195C90.3441 7.42685 90.3441 7.0094 90.3441 7.0094C90.3441 7.0094 93.1806 10.1932 92.4313 9.5141C91.6821 8.83503 85.8089 7.5451 81.587 7.84433V8.67922C85.1591 7.96724 91.5964 10.3657 92.8488 9.93157Z"
            fill="#B08747" />
          <g filter="url(#filter11_d_78_256)">
            <path
              d="M92.4403 9.09665C91.1969 7.42685 90.3535 7.0094 90.3535 7.0094C90.3535 7.0094 89.9266 7.0094 88.6837 6.59195C87.4407 6.17451 88.2568 6.1745 87.013 5.75706C85.7693 5.33962 81.587 5.3396 81.587 5.3396L81.5776 7.8443C85.8289 7.15678 93.6837 10.7664 92.4403 9.09665Z"
              fill="#CB9A4D" />
          </g>
          <path
            d="M62.7764 9.93157C61.5241 9.49742 63.6019 7.84433 63.6019 7.84433C64.5588 6.86401 65.1155 6.54462 66.1158 6.1745L67.7855 5.3396L71.9597 4.5047L74.0469 5.3396C70.7436 5.22875 68.6203 5.75705 66.9506 6.59195C65.2809 7.42685 65.2809 7.0094 65.2809 7.0094C65.2809 7.0094 62.4446 10.1932 63.1938 9.5141C63.943 8.83503 69.8158 7.5451 74.0375 7.84433V8.67922C70.4656 7.96724 64.0287 10.3657 62.7764 9.93157Z"
            fill="#B08747" />
          <g filter="url(#filter12_d_78_256)">
            <path
              d="M63.1848 9.09665C64.4281 7.42685 65.2716 7.0094 65.2716 7.0094C65.2716 7.0094 65.6984 7.0094 66.9413 6.59195C68.1842 6.17451 67.3681 6.1745 68.6118 5.75706C69.8555 5.33962 74.0375 5.3396 74.0375 5.3396L74.0469 7.8443C69.7958 7.15678 61.9415 10.7664 63.1848 9.09665Z"
              fill="#CB9A4D" />
          </g>
          <path
            d="M63.131 14.1728C63.3649 13.7053 63.9283 13.3771 65.0186 12.8537L63.8326 14.4066C63.8326 14.4066 63.3649 15.8092 63.5987 16.2768C63.8326 16.7443 66.4051 17.9132 67.5744 18.3807C68.7437 18.8483 72.9531 19.5496 72.9531 19.5496V20.2509C69.3797 19.5389 66.2714 19.5496 65.0186 19.1155C63.7658 18.6813 62.9807 17.7295 62.513 17.0282C62.0498 16.3337 62.8807 14.6732 63.124 14.1869L63.131 14.1728Z"
            fill="#B08747" />
          <g filter="url(#filter13_d_78_256)">
            <path
              d="M63.3649 16.5106C62.8737 14.8742 65.0186 12.8537 65.0186 12.8537C65.0186 12.8537 64.15 14.0226 65.0019 15.1079C65.8538 16.1933 65.9006 16.2738 66.6389 16.7443C68.7183 17.8684 70.0838 18.1807 72.9531 18.147V19.5496C69.2975 19.0123 63.856 18.147 63.3649 16.5106Z"
              fill="#CB9A4D" />
          </g>
          <path
            d="M55.3434 19.1155C55.7609 18.2806 58.4069 15.4581 60.3534 14.5235L56.5959 19.5329C56.5959 19.5329 55.7609 22.0376 56.1784 22.8725C56.5959 23.7074 61.1884 25.7947 63.2759 26.6296C65.3634 27.4645 72.8784 28.7168 72.8784 28.7168V29.9692L63.2759 27.8819C63.2759 27.8819 56.1784 24.9598 55.3434 23.7074C54.5084 22.4551 54.9259 19.9504 55.3434 19.1155Z"
            fill="#B08747" />
          <g filter="url(#filter14_d_78_256)">
            <path
              d="M55.7609 23.29C55.5146 19.7935 57.9385 17.9067 60.3534 14.5235C58.9736 17.4231 57.9548 19.2021 58.6834 20.7853C59.6071 22.2918 60.2877 22.8672 61.6059 23.7074C65.3181 25.7146 67.7559 26.2724 72.8784 26.2121V28.7168C66.3522 27.7573 61.935 26.641 55.7609 23.29Z"
              fill="#CB9A4D" />
          </g>
          <path
            d="M104.12 25.7947C103.694 24.7172 102.806 22.1936 99.9459 21.6202L97.8586 23.7074C102.471 24.869 99.5284 28.2994 98.6935 29.1343C97.8586 29.9692 92.4318 31.639 90.3445 32.4739C88.2573 33.3088 80.7432 34.5611 80.7432 34.5611V35.8135H92.4318C92.4318 35.8135 99.5361 33.5115 101.616 32.0564C103.695 30.6014 104.547 26.8722 104.12 25.7947Z"
            fill="#B08747" />
          <g filter="url(#filter15_d_78_256)">
            <path
              d="M99.9459 27.4645C101.616 23.7074 97.8586 23.7074 97.8586 23.7074C97.8586 23.7074 98.5871 25.0464 97.8586 26.6296C96.935 28.1361 92.0143 29.5517 92.0143 29.5517C92.0143 29.5517 85.8651 32.1167 80.7432 32.0564V34.5611C88.3835 34.8435 98.2761 31.2215 99.9459 27.4645Z"
              fill="#CB9A4D" />
          </g>
          <path
            d="M49.9585 25.3772C50.3847 24.2997 51.2725 21.7762 54.1333 21.2027L56.2207 23.2899C51.6085 24.4515 54.5508 27.8819 55.3858 28.7168C56.2207 29.5517 61.648 31.2215 63.7354 32.0564C65.8228 32.8913 73.3374 34.1436 73.3374 34.1436V35.396H61.648C61.648 35.396 54.5431 33.094 52.4634 31.6389C50.3837 30.1839 49.5323 26.4547 49.9585 25.3772Z"
            fill="#B08747" />
          <g filter="url(#filter16_d_78_256)">
            <path
              d="M54.1333 27.047C52.4634 23.2899 56.2207 23.2899 56.2207 23.2899C56.2207 23.2899 55.4921 24.6289 56.2207 26.2121C57.1444 27.7185 62.0654 29.1342 62.0654 29.1342C62.0654 29.1342 68.2151 31.6992 73.3374 31.6389V34.1436C65.6965 34.426 55.8032 30.804 54.1333 27.047Z"
              fill="#CB9A4D" />
          </g>
          <path
            d="M107.46 34.9786C107.46 34.9786 106.563 29.7077 103.702 29.1343L102.033 31.639C106.645 32.8005 103.702 37.9007 102.033 39.1531C100.363 40.4054 93.2662 41.2403 93.2662 41.2403L81.5776 43.3276V44.5799H93.2662C93.2662 44.5799 102.875 42.6954 104.955 41.2403C107.034 39.7853 107.46 34.9786 107.46 34.9786Z"
            fill="#B08747" />
          <g filter="url(#filter17_d_78_256)">
            <path
              d="M104.537 35.396C104.525 29.6407 102.033 31.639 102.033 31.639C102.033 31.639 103.285 32.4738 102.45 34.5611C101.615 36.6483 98.2862 38.4381 94.936 39.5705C91.5858 40.7029 85.4713 41.2982 81.5776 40.8229V43.3276C88.7256 44.0556 104.55 41.1513 104.537 35.396Z"
              fill="#CB9A4D" />
          </g>
          <path
            d="M109.964 44.5799C109.964 44.5799 109.068 39.3091 106.207 38.7356L104.537 41.2403C109.149 42.4019 106.207 47.5021 104.537 48.7544C102.868 50.0068 95.7709 50.8417 95.7709 50.8417L81.5776 50.0068V53.7638C81.5776 53.7638 88.2568 54.1813 95.7709 54.1813C103.285 54.1813 105.38 52.2967 107.46 50.8417C109.539 49.3866 109.964 44.5799 109.964 44.5799Z"
            fill="#B08747" />
          <g filter="url(#filter18_d_78_256)">
            <path
              d="M107.042 45.8323C107.505 37.4014 104.537 42.0752 104.537 42.0752C104.537 42.0752 105.79 42.9101 104.955 44.9974C104.12 47.0846 102.945 48.2229 97.4407 50.0068C91.9361 51.7907 83.8616 46.7947 81.5776 45.8323V50.0068C88.2389 53.5287 106.579 54.2631 107.042 45.8323Z"
              fill="#CB9A4D" />
          </g>
          <path
            d="M44.8424 44.5799C44.8424 44.5799 45.7389 39.3091 48.5995 38.7356L50.2693 41.2403C45.6574 42.4019 48.5995 47.5021 50.2693 48.7544C51.9391 50.0068 59.0357 50.8417 59.0357 50.8417L73.229 50.0068V53.7638C73.229 53.7638 66.5498 54.1813 59.0357 54.1813C51.5216 54.1813 49.4267 52.2967 47.3471 50.8417C45.2675 49.3866 44.8424 44.5799 44.8424 44.5799Z"
            fill="#B08747" />
          <g filter="url(#filter19_d_78_256)">
            <path
              d="M47.7646 45.8323C47.3016 37.4014 50.2693 42.0752 50.2693 42.0752C50.2693 42.0752 49.0169 42.9101 49.8518 44.9974C50.6867 47.0846 51.8613 48.2229 57.3659 50.0068C62.8705 51.7907 70.9451 46.7947 73.229 45.8323V50.0068C66.5677 53.5287 48.2275 54.2631 47.7646 45.8323Z"
              fill="#CB9A4D" />
          </g>
          <path
            d="M47.3471 35.396C47.3471 35.396 48.2436 30.1252 51.1042 29.5517L52.774 32.0564C48.1621 33.2179 51.1042 38.3181 52.774 39.5705C54.4438 40.8228 61.5404 41.6577 61.5404 41.6577L73.229 43.745V44.9973H61.5404C61.5404 44.9973 51.9314 43.1128 49.8518 41.6577C47.7722 40.2027 47.3471 35.396 47.3471 35.396Z"
            fill="#B08747" />
          <g filter="url(#filter20_d_78_256)">
            <path
              d="M50.2693 35.8134C50.2819 30.0582 52.774 32.0564 52.774 32.0564C52.774 32.0564 51.5216 32.8913 52.3565 34.9785C53.1914 37.0658 56.5204 38.8556 59.8706 39.9879C63.2208 41.1203 69.3353 41.7157 73.229 41.2403V43.745C66.0811 44.473 50.2566 41.5687 50.2693 35.8134Z"
              fill="#CB9A4D" />
          </g>
          <path
            d="M74.483 39.8586C73.8818 37.2137 73.9684 35.8709 74.483 33.5968C76.7575 33.2381 78.0994 33.188 80.7448 33.5968C81.3515 36.2913 81.1249 37.5694 80.7448 39.8586H74.483Z"
            fill="#E8C987" />
          <path
            d="M74.483 46.9552C73.8818 44.3104 73.9684 42.9675 74.483 40.6935C76.7575 40.3348 78.0994 40.2847 80.7448 40.6935C81.3515 43.388 81.1249 44.6661 80.7448 46.9552H74.483Z"
            fill="#E8C987" />
          <path
            d="M74.9005 54.0519C74.2993 51.407 73.9684 50.0642 74.483 47.7901C76.7575 47.4314 78.0994 47.3813 80.7448 47.7901C81.3515 50.4846 80.7074 51.7627 80.3273 54.0519H74.9005Z"
            fill="#E8C987" />
          <path
            d="M74.9005 54.0519C74.2993 51.407 73.9684 50.0642 74.483 47.7901C76.7575 47.4314 78.0994 47.3813 80.7448 47.7901C81.3515 50.4846 80.7074 51.7627 80.3273 54.0519M74.9005 54.0519V61.566C76.6918 64.5672 78.6559 64.6175 80.3273 61.566V54.0519M74.9005 54.0519H80.3273M74.483 26.5002C73.9684 28.7743 73.8818 30.1171 74.483 32.7619H80.7448C81.1249 30.4728 81.3515 29.1947 80.7448 26.5002C78.0994 26.0914 76.7575 26.1415 74.483 26.5002ZM74.483 33.5968C73.9684 35.8709 73.8818 37.2137 74.483 39.8586H80.7448C81.1249 37.5694 81.3515 36.2913 80.7448 33.5968C78.0994 33.188 76.7575 33.2381 74.483 33.5968ZM74.483 40.6935C73.9684 42.9675 73.8818 44.3104 74.483 46.9552H80.7448C81.1249 44.6661 81.3515 43.388 80.7448 40.6935C78.0994 40.2847 76.7575 40.3348 74.483 40.6935Z"
            stroke="black" stroke-width="0.8349" />
          <path d="M79.9084 54.5987H75.3164V61.2779C77.2294 63.7912 78.2393 63.8867 79.9084 61.2779V54.5987Z"
            fill="#E8C987" stroke="#E8C987" stroke-width="0.8349" />
          <path
            d="M80.3258 27.047H74.8989C74.4815 27.047 74.8989 32.0564 74.8989 32.0564C77.0081 33.0368 80.3258 32.4738 80.3258 32.0564C80.3257 31.6389 80.7432 27.047 80.3258 27.047Z"
            fill="#E8C987" stroke="#E8C987" stroke-width="0.8349" />
          <path
            d="M82.935 13.6886C79.1805 15.2123 77.1234 15.3647 73.5424 13.6886L70.7246 18.2805L73.5424 26.2121H81.9958L85.7528 18.2805L82.935 13.6886Z"
            fill="#EECA82" stroke="black" stroke-opacity="0.52" stroke-width="0.8349" />
          <path
            d="M14 123.818C15.4634 123.86 15.9715 124.106 16.5 124.818C17.4274 126.145 17.7093 126.906 17.5 128.318C19.4422 130.054 20.0465 131.166 20.5 133.318C22.1112 134.9 22.4848 135.775 22.5 137.318L23.5 139.318L25 139.818C25.3696 140.93 25.3991 141.45 24.5 141.818L20.5 139.318L19 135.318C17.9003 134.719 17.3761 134.121 16.5 132.818V129.318L14 127.818H12.5L12 135.318L13.5 138.818V143.818H18L19 144.818L16.5 146.818H18.75H21L23 144.818L24.5 145.818L23.5 147.318L25 148.318L24.5 149.818L22.5 150.318C21.0136 150.779 20.2448 150.823 19 150.318L15 148.818L17 152.068L19 155.318C18.8014 156.971 18.3109 157.371 16.5 156.818L14.5714 153.818L12 149.818V145.818L7.5 138.818V127.818L6 125.818L7.5 121.818L9.5 123.818C10.569 124.935 11.119 125.239 12 125.318L14 123.818Z"
            fill="#E4C690" />
          <path
            d="M20.5 133.318C20.0465 131.166 19.4422 130.054 17.5 128.318C17.7093 126.906 17.4274 126.145 16.5 124.818C15.9715 124.106 15.4634 123.86 14 123.818L12 125.318C11.119 125.239 10.569 124.935 9.5 123.818L7.5 121.818L6 125.818L7.5 127.818V138.818M20.5 133.318C22.1112 134.9 22.4849 135.775 22.5 137.318L23.5 139.318L25 139.818C25.3696 140.93 25.3991 141.45 24.5 141.818L20.5 139.318L19 135.318M20.5 133.318L19 135.318M19 135.318C17.9003 134.719 17.3761 134.121 16.5 132.818V129.318L14 127.818H12.5L12 135.318M12 135.318L13.5 138.818V143.818H18L19 144.818L16.5 146.818H18.75M12 135.318L7.5 138.818M21 146.818L23 144.818L24.5 145.818L23.5 147.318M21 146.818L23.5 147.318M21 146.818L22.5 150.318M21 146.818H18.75M23.5 147.318L25 148.318L24.5 149.818L22.5 150.318M22.5 150.318C21.0136 150.779 20.2448 150.823 19 150.318M19 150.318L15 148.818L17 152.068M19 150.318L18.75 146.818M7.5 138.818L12 145.818V149.818L14.5714 153.818M17 152.068L19 155.318C18.8014 156.971 18.3109 157.371 16.5 156.818L14.5714 153.818M17 152.068L14.5714 153.818"
            stroke="black" />
          <path
            d="M13.4991 121.818C10.1494 120.901 9.18597 121.165 9.49905 123.318C9.87083 124.67 10.312 125.209 12 125.318L14 123.818L13.4991 121.818Z"
            fill="#D2B675" stroke="black" />
          <path
            d="M15 87.8179C16.1899 83.6433 16.6261 81.5765 17 78.3179L23.5 77.8179L21.5 83.3179L20.5 93.3179L18.5 99.3179C17.2196 105.547 16.0309 108.512 13.5 113.318L13 121.818C10.0433 120.907 9.55564 121.652 9 123.318L7.5 121.818L10 110.318C10.9595 102.097 11.635 97.4077 15 87.8179Z"
            fill="url(#paint15_linear_78_256)" stroke="black" />
          <path
            d="M18.5001 87.3179C15.8735 92.2997 15.407 95.158 15.5001 100.318C18.2223 95.3736 18.7477 92.5162 18.5001 87.3179Z"
            fill="white" />
          <path d="M27.5 17.3179H25.5L28.5 24.3179H29.5C30.0829 20.6008 29.0591 19.491 27.5 17.3179Z" fill="#F8C47A"
            stroke="black" />
          <path
            d="M24.5 18.3179V16.8179C24.5 15.3179 28.5 24.3179 28.5 24.3179C25.2957 27.5661 25.0839 30.0214 24.5 34.3179L23.5 68.8179L26.5 77.3179L19.5 78.3179C17.1932 78.5963 16.1894 78.197 15.5 75.3179L18.5 66.3179C19.5629 59.2029 19.6758 55.6977 19.5 49.8179L21.5 18.8179C21.9463 18.4974 22.6472 18.3963 24.5 18.3179Z"
            fill="url(#paint16_linear_78_256)" stroke="black" />
          <path
            d="M38 16.8179H29.5C31.0337 19.4325 31.5208 21.0646 30.5 24.8179C33.3806 28.3669 34.7328 31.0233 36.5 37.3179L36 24.8179L38 17.8179V16.8179Z"
            fill="url(#paint17_linear_78_256)" />
          <path
            d="M46.0004 33.3179L46.5004 16.3179L46.0004 14.8179C48.5 13.3179 46.0004 12.8179 46.0004 12.8179L40 13.3179C38.385 14.0049 37.5172 13.9638 36 12.8179L28.0004 13.3179C24.6262 13.7386 23.3185 14.1941 24.5004 16.3179H28.0004C30.4771 19.9084 30.6933 21.734 30.0004 24.8179C32.8318 28.3698 34.091 31.2273 35.5004 38.3179C37.0143 40.5516 37.4376 41.9208 42.0004 43.3179C44.5148 43.2797 45.2832 40.6259 46.0004 33.3179Z"
            stroke="black" />
          <path
            d="M41.0006 14.8179H45.0006L44.5 32.3179L42.5 40.8179L41.0006 41.3179L36.5001 37.8179L36.0006 27.8179C35.6564 22.585 36.1995 19.7008 41.0006 14.8179Z"
            fill="url(#paint18_linear_78_256)" />
          <path
            d="M141 123.818C139.537 123.86 139.029 124.106 138.5 124.818C137.573 126.145 137.291 126.906 137.5 128.318C135.558 130.054 134.954 131.166 134.5 133.318C132.889 134.9 132.516 135.775 132.501 137.318L131.501 139.318L130.001 139.818C129.631 140.93 129.602 141.45 130.501 141.818L134.5 139.318L136 135.318C137.1 134.719 137.624 134.121 138.5 132.818V129.318L141 127.818H142.5L143 135.318L141.5 138.818V143.818H137L136 144.818L138.5 146.818H136.25H134L132.001 144.818L130.501 145.818L131.501 147.318L130.001 148.318L130.501 149.818L132.501 150.318C133.987 150.779 134.756 150.823 136 150.318L140 148.818L138 152.068L136 155.318C136.199 156.971 136.69 157.371 138.5 156.818L140.429 153.818L143 149.818V145.818L147.5 138.818V127.818L149 125.818L147.5 121.818L145.5 123.818C144.431 124.935 143.881 125.239 143 125.318L141 123.818Z"
            fill="#E4C690" />
          <path
            d="M134.5 133.318C134.954 131.166 135.558 130.054 137.5 128.318C137.291 126.906 137.573 126.145 138.5 124.818C139.029 124.106 139.537 123.86 141 123.818L143 125.318C143.881 125.239 144.431 124.935 145.5 123.818L147.5 121.818L149 125.818L147.5 127.818V138.818M134.5 133.318C132.889 134.9 132.516 135.775 132.501 137.318L131.501 139.318L130.001 139.818C129.631 140.93 129.602 141.45 130.501 141.818L134.5 139.318L136 135.318M134.5 133.318L136 135.318M136 135.318C137.1 134.719 137.624 134.121 138.5 132.818V129.318L141 127.818H142.5L143 135.318M143 135.318L141.5 138.818V143.818H137L136 144.818L138.5 146.818H136.25M143 135.318L147.5 138.818M134 146.818L132.001 144.818L130.501 145.818L131.501 147.318M134 146.818L131.501 147.318M134 146.818L132.501 150.318M134 146.818H136.25M131.501 147.318L130.001 148.318L130.501 149.818L132.501 150.318M132.501 150.318C133.987 150.779 134.756 150.823 136 150.318M136 150.318L140 148.818L138 152.068M136 150.318L136.25 146.818M147.5 138.818L143 145.818V149.818L140.429 153.818M138 152.068L136 155.318C136.199 156.971 136.69 157.371 138.5 156.818L140.429 153.818M138 152.068L140.429 153.818"
            stroke="black" />
          <path
            d="M141.501 121.818C144.851 120.901 145.814 121.165 145.501 123.318C145.129 124.67 144.688 125.209 143 125.318L141 123.818L141.501 121.818Z"
            fill="#D2B675" stroke="black" />
          <path
            d="M140 87.8179C138.81 83.6433 138.374 81.5765 138 78.3179L131.501 77.8179L133.5 83.3179L134.5 93.3179L136.5 99.3179C137.781 105.547 138.969 108.512 141.5 113.318L142 121.818C144.957 120.907 145.444 121.652 146 123.318L147.5 121.818L145 110.318C144.041 102.097 143.365 97.4077 140 87.8179Z"
            fill="url(#paint19_linear_78_256)" stroke="black" />
          <path
            d="M136.5 87.3179C139.127 92.2997 139.594 95.158 139.5 100.318C136.778 95.3736 136.253 92.5162 136.5 87.3179Z"
            fill="white" />
          <path d="M127.501 17.3179H129.501L126.501 24.3179H125.501C124.918 20.6008 125.942 19.491 127.501 17.3179Z"
            fill="#F8C47A" stroke="black" />
          <path
            d="M130.5 18.3179V16.8179C130.5 15.3179 126.5 24.3179 126.5 24.3179C129.705 27.5661 129.916 30.0214 130.5 34.3179L131.5 68.8179L128.5 77.3179L135.5 78.3179C137.807 78.5963 138.811 78.197 139.5 75.3179L136.5 66.3179C135.437 59.2029 135.324 55.6977 135.5 49.8179L133.5 18.8179C133.054 18.4974 132.353 18.3963 130.5 18.3179Z"
            fill="url(#paint20_linear_78_256)" stroke="black" />
          <path
            d="M117.001 16.8179H125.501C123.967 19.4325 123.48 21.0646 124.501 24.8179C121.621 28.3669 120.268 31.0233 118.501 37.3179L119.001 24.8179L117.001 17.8179V16.8179Z"
            fill="url(#paint21_linear_78_256)" />
          <path
            d="M109.001 33.3179L108.501 16.3179L109.001 14.8179C106.501 13.3179 109.001 12.8179 109.001 12.8179L115.001 13.3179C116.616 14.0049 117.484 13.9638 119.001 12.8179L127 13.3179C130.374 13.7386 131.682 14.1941 130.5 16.3179H127C124.524 19.9084 124.307 21.734 125 24.8179C122.169 28.3698 120.91 31.2273 119.5 38.3179C117.987 40.5516 117.563 41.9208 113.001 43.3179C110.486 43.2797 109.718 40.6259 109.001 33.3179Z"
            stroke="black" />
          <path
            d="M114.001 14.8179H110.001L110.501 32.3179L112.501 40.8179L114.001 41.3179L118.501 37.8179L119 27.8179C119.345 22.585 118.801 19.7008 114.001 14.8179Z"
            fill="url(#paint22_linear_78_256)" />
            <circle cx="78" cy="95" r="5" fill="yellow" stroke="black" stroke-width="1" @click="
          showInfo(
            'bones',
            'Colone Vertébrale',
            'La colonne vertébrale est la clé de voute du corps, mais permet aussi d\'envoyer les ordres à certaines zones par l\'intermédiaire du système nerveux central. En cas de rupture en un point, plus la blessure est haute, plus les conséquences sont sévères.'
          )
          " /><!-- VERTEBRES -->
          <circle cx="78" cy="20" r="4" fill="yellow" stroke="black" stroke-width="1" @click="
          showInfo(
            'bones',
            'Manubrium',
            'Le manubrium assure le lien entre l\'épaule et le tronc'
          )
          " /><!-- MANUBRIUM -->
          <circle cx="78" cy="45" r="4" fill="yellow" stroke="black" stroke-width="1" @click="
          showInfo(
            'bones',
            'Sternum',
            'Il sert à protéger les organes thoraciques des traumatismes et de servir d\'attache osseuse à divers muscles'
          )
          " /><!-- STERNUM -->
          <circle cx="95" cy="42" r="4" fill="yellow" stroke="black" stroke-width="1" @click="
          showInfo(
            'bones',
            'Côtes',
            'Les côtes forment la cage thoracique qui protège le cœur et les poumons des éventuels chocs extérieurs'
          )
          " /><!-- CÔTES -->
          <circle cx="41" cy="103" r="4" fill="yellow" stroke="black" stroke-width="1" @click="
          showInfo(
            'bones',
            'Ilion',
            'L\'ilion est l\'un des trois os qui sont soudés chez l\'adulte pour former le bassin'
          )
          " /><!-- Ilion -->
          <circle cx="52" cy="112" r="4" fill="yellow" stroke="black" stroke-width="1" @click="
          showInfo(
            'bones',
            'Os iliaque',
            'L\'os iliaque s\'articule avec le fémur par l\'articulation coxo-fémorale (entre l\'os iliaque et le fémur) qui assure le transfert des charges du tronc au membre inférieur'
          )
          " /><!-- Os iliaque -->
          <circle cx="78" cy="122" r="4" fill="yellow" stroke="black" stroke-width="1" @click="
          showInfo(
            'bones',
            'Sacrum',
            'Le sacrum est un os qui réunit la colonne vertébrale au bassin. Il joue un rôle de support du poids du haut du corps et de protection des nerfs rachidiens. Il peut être affecté par différentes pathologies comme une fracture, une malformation et déformation ou encore une tumeur'
          )
          " /><!-- Sacrum -->
          <circle cx="121" cy="143" r="4" fill="yellow" stroke="black" stroke-width="1" @click="
          showInfo(
            'bones',
            'Fémur',
            'Le fémur est l\'os le plus long et le plus résistant du corps. Il se situe dans la cuisse et relie le bassin à l\'articulation du genou. Nous possédons deux fémurs (un dans chaque cuisse). Ils jouent un rôle essentiel car ils portent le poids de la partie supérieure de notre corps, lorsque nous nous tenons debout'
          )
          " /><!-- FEMUR -->
            
          <defs>
            <filter id="filter0_d_78_256" x="33.0579" y="95.9262" width="88.8223" height="50.094"
              filterUnits="userSpaceOnUse" color-interpolation-filters="sRGB">
              <feFlood flood-opacity="0" result="BackgroundImageFix" />
              <feColorMatrix in="SourceAlpha" type="matrix" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"
                result="hardAlpha" />
              <feOffset dy="3.3396" />
              <feGaussianBlur stdDeviation="1.6698" />
              <feComposite in2="hardAlpha" operator="out" />
              <feColorMatrix type="matrix" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.25 0" />
              <feBlend mode="normal" in2="BackgroundImageFix" result="effect1_dropShadow_78_256" />
              <feBlend mode="normal" in="SourceGraphic" in2="effect1_dropShadow_78_256" result="shape" />
            </filter>
            <filter id="filter1_d_78_256" x="24.2429" y="131.583" width="30.5142" height="95.3296"
              filterUnits="userSpaceOnUse" color-interpolation-filters="sRGB">
              <feFlood flood-opacity="0" result="BackgroundImageFix" />
              <feColorMatrix in="SourceAlpha" type="matrix" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"
                result="hardAlpha" />
              <feOffset dy="3.3396" />
              <feGaussianBlur stdDeviation="1.6698" />
              <feComposite in2="hardAlpha" operator="out" />
              <feColorMatrix type="matrix" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.34 0" />
              <feBlend mode="normal" in2="BackgroundImageFix" result="effect1_dropShadow_78_256" />
              <feBlend mode="normal" in="SourceGraphic" in2="effect1_dropShadow_78_256" result="shape" />
            </filter>
            <filter id="filter2_d_78_256" x="100.243" y="131.583" width="30.5142" height="95.3296"
              filterUnits="userSpaceOnUse" color-interpolation-filters="sRGB">
              <feFlood flood-opacity="0" result="BackgroundImageFix" />
              <feColorMatrix in="SourceAlpha" type="matrix" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"
                result="hardAlpha" />
              <feOffset dy="3.3396" />
              <feGaussianBlur stdDeviation="1.6698" />
              <feComposite in2="hardAlpha" operator="out" />
              <feColorMatrix type="matrix" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.34 0" />
              <feBlend mode="normal" in2="BackgroundImageFix" result="effect1_dropShadow_78_256" />
              <feBlend mode="normal" in="SourceGraphic" in2="effect1_dropShadow_78_256" result="shape" />
            </filter>
            <filter id="filter3_d_78_256" x="77.8245" y="53.3756" width="38.5693" height="26.0497"
              filterUnits="userSpaceOnUse" color-interpolation-filters="sRGB">
              <feFlood flood-opacity="0" result="BackgroundImageFix" />
              <feColorMatrix in="SourceAlpha" type="matrix" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"
                result="hardAlpha" />
              <feOffset dy="3.3396" />
              <feGaussianBlur stdDeviation="1.6698" />
              <feComposite in2="hardAlpha" operator="out" />
              <feColorMatrix type="matrix" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.42 0" />
              <feBlend mode="normal" in2="BackgroundImageFix" result="effect1_dropShadow_78_256" />
              <feBlend mode="normal" in="SourceGraphic" in2="effect1_dropShadow_78_256" result="shape" />
            </filter>
            <filter id="filter4_d_78_256" x="39.4163" y="52.9525" width="38.5723" height="26.2756"
              filterUnits="userSpaceOnUse" color-interpolation-filters="sRGB">
              <feFlood flood-opacity="0" result="BackgroundImageFix" />
              <feColorMatrix in="SourceAlpha" type="matrix" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"
                result="hardAlpha" />
              <feOffset dy="3.3396" />
              <feGaussianBlur stdDeviation="1.6698" />
              <feComposite in2="hardAlpha" operator="out" />
              <feColorMatrix type="matrix" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.42 0" />
              <feBlend mode="normal" in2="BackgroundImageFix" result="effect1_dropShadow_78_256" />
              <feBlend mode="normal" in="SourceGraphic" in2="effect1_dropShadow_78_256" result="shape" />
            </filter>
            <filter id="filter5_d_78_256" x="76.8796" y="45.6109" width="37.8413" height="24.7534"
              filterUnits="userSpaceOnUse" color-interpolation-filters="sRGB">
              <feFlood flood-opacity="0" result="BackgroundImageFix" />
              <feColorMatrix in="SourceAlpha" type="matrix" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"
                result="hardAlpha" />
              <feOffset dy="3.3396" />
              <feGaussianBlur stdDeviation="1.6698" />
              <feComposite in2="hardAlpha" operator="out" />
              <feColorMatrix type="matrix" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.42 0" />
              <feBlend mode="normal" in2="BackgroundImageFix" result="effect1_dropShadow_78_256" />
              <feBlend mode="normal" in="SourceGraphic" in2="effect1_dropShadow_78_256" result="shape" />
            </filter>
            <filter id="filter6_d_78_256" x="41.0857" y="45.6174" width="37.8652" height="24.4269"
              filterUnits="userSpaceOnUse" color-interpolation-filters="sRGB">
              <feFlood flood-opacity="0" result="BackgroundImageFix" />
              <feColorMatrix in="SourceAlpha" type="matrix" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"
                result="hardAlpha" />
              <feOffset dy="3.3396" />
              <feGaussianBlur stdDeviation="1.6698" />
              <feComposite in2="hardAlpha" operator="out" />
              <feColorMatrix type="matrix" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.42 0" />
              <feBlend mode="normal" in2="BackgroundImageFix" result="effect1_dropShadow_78_256" />
              <feBlend mode="normal" in="SourceGraphic" in2="effect1_dropShadow_78_256" result="shape" />
            </filter>
            <filter id="filter7_d_78_256" x="78.2385" y="63.6697" width="39.7417" height="27.3576"
              filterUnits="userSpaceOnUse" color-interpolation-filters="sRGB">
              <feFlood flood-opacity="0" result="BackgroundImageFix" />
              <feColorMatrix in="SourceAlpha" type="matrix" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"
                result="hardAlpha" />
              <feOffset dy="3.3396" />
              <feGaussianBlur stdDeviation="1.6698" />
              <feComposite in2="hardAlpha" operator="out" />
              <feColorMatrix type="matrix" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.42 0" />
              <feBlend mode="normal" in2="BackgroundImageFix" result="effect1_dropShadow_78_256" />
              <feBlend mode="normal" in="SourceGraphic" in2="effect1_dropShadow_78_256" result="shape" />
            </filter>
            <filter id="filter8_d_78_256" x="37.7463" y="63.674" width="39.7412" height="27.2428"
              filterUnits="userSpaceOnUse" color-interpolation-filters="sRGB">
              <feFlood flood-opacity="0" result="BackgroundImageFix" />
              <feColorMatrix in="SourceAlpha" type="matrix" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"
                result="hardAlpha" />
              <feOffset dy="3.3396" />
              <feGaussianBlur stdDeviation="1.6698" />
              <feComposite in2="hardAlpha" operator="out" />
              <feColorMatrix type="matrix" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.42 0" />
              <feBlend mode="normal" in2="BackgroundImageFix" result="effect1_dropShadow_78_256" />
              <feBlend mode="normal" in="SourceGraphic" in2="effect1_dropShadow_78_256" result="shape" />
            </filter>
            <filter id="filter9_d_78_256" x="78.656" y="6.59198" width="23.812" height="20.8725"
              filterUnits="userSpaceOnUse" color-interpolation-filters="sRGB">
              <feFlood flood-opacity="0" result="BackgroundImageFix" />
              <feColorMatrix in="SourceAlpha" type="matrix" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"
                result="hardAlpha" />
              <feOffset dy="-3.3396" />
              <feGaussianBlur stdDeviation="1.6698" />
              <feComposite in2="hardAlpha" operator="out" />
              <feColorMatrix type="matrix" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.7 0" />
              <feBlend mode="normal" in2="BackgroundImageFix" result="effect1_dropShadow_78_256" />
              <feBlend mode="normal" in="SourceGraphic" in2="effect1_dropShadow_78_256" result="shape" />
            </filter>
            <filter id="filter10_d_78_256" x="79.7075" y="9.53083" width="13.3981" height="10.4363"
              filterUnits="userSpaceOnUse" color-interpolation-filters="sRGB">
              <feFlood flood-opacity="0" result="BackgroundImageFix" />
              <feColorMatrix in="SourceAlpha" type="matrix" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"
                result="hardAlpha" />
              <feOffset dy="-1.87018" />
              <feGaussianBlur stdDeviation="0.935088" />
              <feComposite in2="hardAlpha" operator="out" />
              <feColorMatrix type="matrix" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.7 0" />
              <feBlend mode="normal" in2="BackgroundImageFix" result="effect1_dropShadow_78_256" />
              <feBlend mode="normal" in="SourceGraphic" in2="effect1_dropShadow_78_256" result="shape" />
            </filter>
            <filter id="filter11_d_78_256" x="79.7075" y="1.59925" width="14.735" height="7.94314"
              filterUnits="userSpaceOnUse" color-interpolation-filters="sRGB">
              <feFlood flood-opacity="0" result="BackgroundImageFix" />
              <feColorMatrix in="SourceAlpha" type="matrix" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"
                result="hardAlpha" />
              <feOffset dy="-1.87018" />
              <feGaussianBlur stdDeviation="0.935088" />
              <feComposite in2="hardAlpha" operator="out" />
              <feColorMatrix type="matrix" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.7 0" />
              <feBlend mode="normal" in2="BackgroundImageFix" result="effect1_dropShadow_78_256" />
              <feBlend mode="normal" in="SourceGraphic" in2="effect1_dropShadow_78_256" result="shape" />
            </filter>
            <filter id="filter12_d_78_256" x="61.183" y="1.59925" width="14.734" height="7.94314"
              filterUnits="userSpaceOnUse" color-interpolation-filters="sRGB">
              <feFlood flood-opacity="0" result="BackgroundImageFix" />
              <feColorMatrix in="SourceAlpha" type="matrix" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"
                result="hardAlpha" />
              <feOffset dy="-1.87018" />
              <feGaussianBlur stdDeviation="0.935088" />
              <feComposite in2="hardAlpha" operator="out" />
              <feColorMatrix type="matrix" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.7 0" />
              <feBlend mode="normal" in2="BackgroundImageFix" result="effect1_dropShadow_78_256" />
              <feBlend mode="normal" in="SourceGraphic" in2="effect1_dropShadow_78_256" result="shape" />
            </filter>
            <filter id="filter13_d_78_256" x="61.4218" y="9.11335" width="13.4015" height="10.4363"
              filterUnits="userSpaceOnUse" color-interpolation-filters="sRGB">
              <feFlood flood-opacity="0" result="BackgroundImageFix" />
              <feColorMatrix in="SourceAlpha" type="matrix" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"
                result="hardAlpha" />
              <feOffset dy="-1.87018" />
              <feGaussianBlur stdDeviation="0.935088" />
              <feComposite in2="hardAlpha" operator="out" />
              <feColorMatrix type="matrix" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.7 0" />
              <feBlend mode="normal" in2="BackgroundImageFix" result="effect1_dropShadow_78_256" />
              <feBlend mode="normal" in="SourceGraphic" in2="effect1_dropShadow_78_256" result="shape" />
            </filter>
            <filter id="filter14_d_78_256" x="52.4041" y="7.84433" width="23.814" height="20.8725"
              filterUnits="userSpaceOnUse" color-interpolation-filters="sRGB">
              <feFlood flood-opacity="0" result="BackgroundImageFix" />
              <feColorMatrix in="SourceAlpha" type="matrix" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"
                result="hardAlpha" />
              <feOffset dy="-3.3396" />
              <feGaussianBlur stdDeviation="1.6698" />
              <feComposite in2="hardAlpha" operator="out" />
              <feColorMatrix type="matrix" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.7 0" />
              <feBlend mode="normal" in2="BackgroundImageFix" result="effect1_dropShadow_78_256" />
              <feBlend mode="normal" in="SourceGraphic" in2="effect1_dropShadow_78_256" result="shape" />
            </filter>
            <filter id="filter15_d_78_256" x="77.4036" y="17.0282" width="26.3096" height="17.5484"
              filterUnits="userSpaceOnUse" color-interpolation-filters="sRGB">
              <feFlood flood-opacity="0" result="BackgroundImageFix" />
              <feColorMatrix in="SourceAlpha" type="matrix" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"
                result="hardAlpha" />
              <feOffset dy="-3.3396" />
              <feGaussianBlur stdDeviation="1.6698" />
              <feComposite in2="hardAlpha" operator="out" />
              <feColorMatrix type="matrix" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.7 0" />
              <feBlend mode="normal" in2="BackgroundImageFix" result="effect1_dropShadow_78_256" />
              <feBlend mode="normal" in="SourceGraphic" in2="effect1_dropShadow_78_256" result="shape" />
            </filter>
            <filter id="filter16_d_78_256" x="50.366" y="16.6107" width="26.311" height="17.5484"
              filterUnits="userSpaceOnUse" color-interpolation-filters="sRGB">
              <feFlood flood-opacity="0" result="BackgroundImageFix" />
              <feColorMatrix in="SourceAlpha" type="matrix" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"
                result="hardAlpha" />
              <feOffset dy="-3.3396" />
              <feGaussianBlur stdDeviation="1.6698" />
              <feComposite in2="hardAlpha" operator="out" />
              <feColorMatrix type="matrix" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.7 0" />
              <feBlend mode="normal" in2="BackgroundImageFix" result="effect1_dropShadow_78_256" />
              <feBlend mode="normal" in="SourceGraphic" in2="effect1_dropShadow_78_256" result="shape" />
            </filter>
            <filter id="filter17_d_78_256" x="78.238" y="24.6241" width="29.6392" height="18.8137"
              filterUnits="userSpaceOnUse" color-interpolation-filters="sRGB">
              <feFlood flood-opacity="0" result="BackgroundImageFix" />
              <feColorMatrix in="SourceAlpha" type="matrix" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"
                result="hardAlpha" />
              <feOffset dy="-3.3396" />
              <feGaussianBlur stdDeviation="1.6698" />
              <feComposite in2="hardAlpha" operator="out" />
              <feColorMatrix type="matrix" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.7 0" />
              <feBlend mode="normal" in2="BackgroundImageFix" result="effect1_dropShadow_78_256" />
              <feBlend mode="normal" in="SourceGraphic" in2="effect1_dropShadow_78_256" result="shape" />
            </filter>
            <filter id="filter18_d_78_256" x="78.238" y="34.104" width="32.1929" height="18.3932"
              filterUnits="userSpaceOnUse" color-interpolation-filters="sRGB">
              <feFlood flood-opacity="0" result="BackgroundImageFix" />
              <feColorMatrix in="SourceAlpha" type="matrix" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"
                result="hardAlpha" />
              <feOffset dy="-3.3396" />
              <feGaussianBlur stdDeviation="1.6698" />
              <feComposite in2="hardAlpha" operator="out" />
              <feColorMatrix type="matrix" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.7 0" />
              <feBlend mode="normal" in2="BackgroundImageFix" result="effect1_dropShadow_78_256" />
              <feBlend mode="normal" in="SourceGraphic" in2="effect1_dropShadow_78_256" result="shape" />
            </filter>
            <filter id="filter19_d_78_256" x="44.3757" y="34.104" width="32.1929" height="18.3932"
              filterUnits="userSpaceOnUse" color-interpolation-filters="sRGB">
              <feFlood flood-opacity="0" result="BackgroundImageFix" />
              <feColorMatrix in="SourceAlpha" type="matrix" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"
                result="hardAlpha" />
              <feOffset dy="-3.3396" />
              <feGaussianBlur stdDeviation="1.6698" />
              <feComposite in2="hardAlpha" operator="out" />
              <feColorMatrix type="matrix" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.7 0" />
              <feBlend mode="normal" in2="BackgroundImageFix" result="effect1_dropShadow_78_256" />
              <feBlend mode="normal" in="SourceGraphic" in2="effect1_dropShadow_78_256" result="shape" />
            </filter>
            <filter id="filter20_d_78_256" x="46.9294" y="25.0416" width="29.6392" height="18.8137"
              filterUnits="userSpaceOnUse" color-interpolation-filters="sRGB">
              <feFlood flood-opacity="0" result="BackgroundImageFix" />
              <feColorMatrix in="SourceAlpha" type="matrix" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"
                result="hardAlpha" />
              <feOffset dy="-3.3396" />
              <feGaussianBlur stdDeviation="1.6698" />
              <feComposite in2="hardAlpha" operator="out" />
              <feColorMatrix type="matrix" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.7 0" />
              <feBlend mode="normal" in2="BackgroundImageFix" result="effect1_dropShadow_78_256" />
              <feBlend mode="normal" in="SourceGraphic" in2="effect1_dropShadow_78_256" result="shape" />
            </filter>
            <linearGradient id="paint0_linear_78_256" x1="77.6876" y1="107.615" x2="77.6876" y2="134.044"
              gradientUnits="userSpaceOnUse">
              <stop stop-color="#C78620" />
              <stop offset="1" stop-color="#B5660D" />
            </linearGradient>
            <linearGradient id="paint1_linear_78_256" x1="111.026" y1="128.07" x2="101.425" y2="139.341"
              gradientUnits="userSpaceOnUse">
              <stop stop-color="#E9D1A0" />
              <stop offset="1" stop-color="#C78F39" />
            </linearGradient>
            <linearGradient id="paint2_linear_78_256" x1="44.2342" y1="127.673" x2="54.6307" y2="139.044"
              gradientUnits="userSpaceOnUse">
              <stop stop-color="#E9D1A0" />
              <stop offset="1" stop-color="#C78F39" />
            </linearGradient>
            <linearGradient id="paint3_linear_78_256" x1="58.4274" y1="141.011" x2="73.0381" y2="151.03"
              gradientUnits="userSpaceOnUse">
              <stop stop-color="#D59E2E" />
              <stop offset="1" stop-color="#B5650C" />
            </linearGradient>
            <linearGradient id="paint4_linear_78_256" x1="96.4154" y1="141.014" x2="81.8101" y2="151.034"
              gradientUnits="userSpaceOnUse">
              <stop stop-color="#D59E2E" />
              <stop offset="1" stop-color="#B5650C" />
            </linearGradient>
            <linearGradient id="paint5_linear_78_256" x1="46.3213" y1="100.101" x2="70.5334" y2="136.419"
              gradientUnits="userSpaceOnUse">
              <stop stop-color="#B4640C" />
              <stop offset="1" stop-color="#DEAE38" />
            </linearGradient>
            <linearGradient id="paint6_linear_78_256" x1="62.1843" y1="108.032" x2="43.0015" y2="106.869"
              gradientUnits="userSpaceOnUse">
              <stop offset="0.5" stop-color="#CF9435" />
              <stop offset="1" stop-color="#E8C25D" />
            </linearGradient>
            <linearGradient id="paint7_linear_78_256" x1="108.616" y1="100.101" x2="84.4046" y2="136.421"
              gradientUnits="userSpaceOnUse">
              <stop stop-color="#B4640C" />
              <stop offset="1" stop-color="#DEAE38" />
            </linearGradient>
            <linearGradient id="paint8_linear_78_256" x1="92.7515" y1="108.032" x2="111.936" y2="106.869"
              gradientUnits="userSpaceOnUse">
              <stop offset="0.5" stop-color="#CF9435" />
              <stop offset="1" stop-color="#E8C25D" />
            </linearGradient>
            <linearGradient id="paint9_linear_78_256" x1="30.6136" y1="130.358" x2="43.8651" y2="166.486"
              gradientUnits="userSpaceOnUse">
              <stop stop-color="#C88720" />
              <stop offset="1" stop-color="#D8A331" />
            </linearGradient>
            <linearGradient id="paint10_linear_78_256" x1="42.75" y1="218.861" x2="20.8439" y2="238.139"
              gradientUnits="userSpaceOnUse">
              <stop stop-color="#C88720" />
              <stop offset="1" stop-color="#D8A331" />
            </linearGradient>
            <linearGradient id="paint11_linear_78_256" x1="47.7155" y1="217.2" x2="25.6324" y2="243.802"
              gradientUnits="userSpaceOnUse">
              <stop stop-color="#C88720" />
              <stop offset="1" stop-color="#D8A331" />
            </linearGradient>
            <linearGradient id="paint12_linear_78_256" x1="124.386" y1="130.358" x2="111.135" y2="166.486"
              gradientUnits="userSpaceOnUse">
              <stop stop-color="#C88720" />
              <stop offset="1" stop-color="#D8A331" />
            </linearGradient>
            <linearGradient id="paint13_linear_78_256" x1="112.25" y1="218.861" x2="134.157" y2="238.139"
              gradientUnits="userSpaceOnUse">
              <stop stop-color="#C88720" />
              <stop offset="1" stop-color="#D8A331" />
            </linearGradient>
            <linearGradient id="paint14_linear_78_256" x1="107.285" y1="217.2" x2="129.368" y2="243.802"
              gradientUnits="userSpaceOnUse">
              <stop stop-color="#C88720" />
              <stop offset="1" stop-color="#D8A331" />
            </linearGradient>
            <linearGradient id="paint15_linear_78_256" x1="15.5" y1="77.8179" x2="15.5" y2="123.318"
              gradientUnits="userSpaceOnUse">
              <stop stop-color="#DCAF57" />
              <stop offset="1" stop-color="#AE9150" />
            </linearGradient>
            <linearGradient id="paint16_linear_78_256" x1="22" y1="16.6493" x2="22" y2="78.3923"
              gradientUnits="userSpaceOnUse">
              <stop stop-color="#FFD48E" />
              <stop offset="1" stop-color="#F7D267" />
            </linearGradient>
            <linearGradient id="paint17_linear_78_256" x1="33.75" y1="16.8179" x2="33.75" y2="37.3179"
              gradientUnits="userSpaceOnUse">
              <stop stop-color="#F1CFA6" />
              <stop offset="1" stop-color="#DEB151" />
            </linearGradient>
            <linearGradient id="paint18_linear_78_256" x1="40.4588" y1="14.8179" x2="40.4588" y2="41.3179"
              gradientUnits="userSpaceOnUse">
              <stop stop-color="#DAB049" />
              <stop offset="1" stop-color="#F3C69C" />
            </linearGradient>
            <linearGradient id="paint19_linear_78_256" x1="139.5" y1="77.8179" x2="139.5" y2="123.318"
              gradientUnits="userSpaceOnUse">
              <stop stop-color="#DCAF57" />
              <stop offset="1" stop-color="#AE9150" />
            </linearGradient>
            <linearGradient id="paint20_linear_78_256" x1="133" y1="16.6493" x2="133" y2="78.3923"
              gradientUnits="userSpaceOnUse">
              <stop stop-color="#FFD48E" />
              <stop offset="1" stop-color="#F7D267" />
            </linearGradient>
            <linearGradient id="paint21_linear_78_256" x1="121.251" y1="16.8179" x2="121.251" y2="37.3179"
              gradientUnits="userSpaceOnUse">
              <stop stop-color="#F1CFA6" />
              <stop offset="1" stop-color="#DEB151" />
            </linearGradient>
            <linearGradient id="paint22_linear_78_256" x1="114.542" y1="14.8179" x2="114.542" y2="41.3179"
              gradientUnits="userSpaceOnUse">
              <stop stop-color="#DAB049" />
              <stop offset="1" stop-color="#F3C69C" />
            </linearGradient>
          </defs>
        </svg>
      </div>
      <transition name="fade">
        <div class="info-container">
          <div class="title-container">
            <h3 v-if="selectedBonesPart" :class="{ active: selectedBonesPart }">
              {{ selectedBonesPart.name }}
            </h3>
          </div>
          <div class="text-container">
            <p v-if="selectedBonesPart" :class="{ active: selectedBonesPart }">
              {{ selectedBonesPart.description }}
            </p>
          </div>
        </div>
      </transition>
    </div>
</template>

<script>
export default {
  data() {
    return {
      selectedHeartPart: null, // Stores selected part info for heart
      selectedBodyPart: null, // Stores selected part info for body
      selectedBonesPart: null, // Stores selected part info for bones
    };
  },
  methods: {
  showInfo(section, name, description) {
    if (section === "heart") {
      this.selectedHeartPart = { name, description };
      this.selectedBodyPart = null;
      this.selectedBonesPart = null; // Reset bones info when heart is clicked
    } else if (section === "body") {
      this.selectedBodyPart = { name, description };
      this.selectedHeartPart = null;
      this.selectedBonesPart = null; // Reset bones info when body is clicked
    } else if (section === "bones") {
      this.selectedBonesPart = { name, description };
      this.selectedHeartPart = null;
      this.selectedBodyPart = null; // Reset heart and body info when bones is clicked
    }
  },
},
};
</script>

<style scoped>
@keyframes appear {
  100% {
    opacity: 1;
    left: 0;
  }
}

.fade-enter-active,
.fade-leave-active {
  transition: opacity 0.6s ease, transform 0.6s ease;
}

.fade-enter-from,
.fade-leave-to {
  opacity: 0;
  transform: translateY(10px);
}

.active {
  opacity: 1;
  animation: appear 0.2s ease-in-out forwards;
}

.body-container {
  max-width: 300px;
  max-height: 900px;
  margin: 0 auto;

  svg {
    width: 100%;
    height: 100%;
  }
}

circle {
  cursor: pointer;
  position: relative;
  z-index: 5;
  transition: 0.2s ease-in-out;

  &:hover {
    r: 7px;
    fill: rgb(255, 0, 0);
  }
}

.wrapper {
  height: auto;
  display: grid;
  grid-template-columns: 1fr 1fr;
  grid-template-rows: 1fr 1fr;
  width: 98%;
  /* margin: 50px auto; */

  .part-container {
    width: 100%;
    height: auto;
    margin: 0 auto;
  }

  .info-container {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    min-height: 325px;
    width: 100%;
    height: 100%;
    margin: 0 auto;
    opacity: 1;
    position: relative;
    overflow-x: hidden;

    .title-container {
      position: relative;
      line-height: 1.5rem;
      width: 100%;
      height: 25%;
      overflow-x: hidden;
      margin: 0 auto;

      h3 {
        animation: appear 0.2s ease-in-out forwards;
        left: 50%;
        position: relative;
        animation: appear 0.2s ease-in-out forwards;
        height: 100%;
      }
    }

    .text-container {
      position: relative;
      line-height: 1.5rem;
      width: 100%;
      height: 100%;
      overflow-x: hidden;
      margin: 0 auto;

      p {
        left: 50%;
        position: relative;
        animation: appear 0.4s ease-in-out forwards;
        height: 100%;
      }
    }
  }
}

@media (min-width: 320px) and (max-width: 991px) {
  .wrapper {
    display: grid;
    grid-template-columns: 1fr;
    grid-template-rows: 1fr;
    width: 100%;
    margin: 0 auto;
    gap: 50px;

    .heart-container {
      width: 100%;
      height: 50%;
      margin: 0 auto;
    }

    .info-container {
      display: flex;
      flex-direction: column;
      width: 100%;
      height: 100%;
      margin: 0 auto;
      justify-content: center;
      align-items: center;

      .title-container {
        width: 100%;
        height: 25%;
        margin: 0 auto;
      }

      .text-container {
        width: 100%;
        height: 100%;
        margin: 0 auto;

        p {
          width: 75%;
          margin: 0 auto;
        }
      }
    }
  }
}
</style>
