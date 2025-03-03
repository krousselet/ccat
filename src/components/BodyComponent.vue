<template>
  <div class=title-container>
    <h2>Coeur</h2>
  </div>
  <div class="wrapper">
    <div class="heart-container">
      <svg xmlns="http://www.w3.org/2000/svg" width="187" height="269" viewBox="0 0 187 269" fill="none">
        <path
            d="M130.705 129.8C130.471 128.886 130.957 128.432 132.794 127.711C134.56 128.154 135.102 128.701 134.883 130.497C135.191 131.758 134.473 132.086 132.794 131.889C131.209 132.221 130.669 131.902 130.705 129.8Z"
            fill="#656464"
            stroke="black"
            stroke-width="1.3926"
          />
          <path
            d="M46.4523 166.704C44.8283 159.255 44.6512 155.718 50.6301 154.867C53.8079 153.453 56.0495 153.291 60.3781 153.474C63.2636 155.436 64.9403 155.743 68.0374 154.867C69.1047 152.402 70.2063 151.687 72.9115 151.386C75.9078 155.863 77.9768 158.083 83.356 160.809C89.5044 164.107 93.0517 166.417 98.6746 172.275C102.659 178.766 105.62 181.359 112.601 183.415L129.312 198.734C130.493 201.327 129.952 201.76 128.615 202.215L93.1042 200.823C80.0088 198.557 75.4506 196.566 69.43 192.467C53.0357 177.946 48.8926 172.84 46.4523 166.704Z"
            fill="url(#paint0_linear_51_3)"
             stroke="black"
          />
          <circle cx="65" cy="165" r="5" fill="yellow" stroke="black" stroke-width="1"
          @click="showInfo('heart', 'Ventricule droit', 'Le ventricule droit se contracte et envoie le sang par la valvule pulmonaire dans l\'artère pulmonaire, puis dans les poumons. Simultanément, le sang riche en oxygène provenant des poumons est amené au cœur par les veines pulmonaires.')"
        />
          <path
            d="M109.815 110.304C104.952 110.506 103.729 111.549 102.156 113.785C102.344 121.972 101.615 126.423 97.9782 133.978C96.9966 140.152 97.0507 143.52 98.6745 149.297L120.26 172.274C120.239 168.056 120.65 166.613 121.652 164.615C120.777 156.121 121.446 154.073 123.045 151.386C128.631 142.382 127.568 138.174 126.526 130.497C123.731 113.924 118.897 112.235 109.815 110.304Z"
            fill="url(#paint1_linear_51_3)"
            stroke="black"
            stroke-width="1.3926"
          />
          <circle cx="113" cy="125" r="5" fill="yellow" stroke="black" stroke-width="1"
          @click="showInfo('heart','Ventricule gauche', 'Le ventricule gauche se contracte et propulse le sang dans l\'aorte. La valve située au départ de l\'aorte se ferme. Le sang est distribué dans tout l\'organisme. Les artères coronaires, alimentées par l\'aorte, assurent l\'approvisionnement en sang oxygéné du cœur lui-même.')"
        />
          <path
            d="M145.326 108.215C135.375 105.784 130.143 106.139 120.956 107.519C125.745 114.126 128.422 117.838 130.007 127.015H136.274C135.448 119.721 136.842 115.611 145.326 108.215Z"
            fill="url(#paint2_linear_51_3)"
            stroke="black"
            stroke-width="1.3926"
            @click="showInfo('heart','Valve aortique', 'La valve aortique contrôle le passage du sang entre le ventricule gauche et l\'aorte.')"
          />
          <circle cx="110" cy="109" r="5" fill="yellow" stroke="black" stroke-width="1"
          @click="showInfo('heart','Valve aortique', 'La valve aortique contrôle le passage du sang entre le ventricule gauche et l\'aorte.')"
        />
        <path 
        d="M145.326 108.215C135.375 105.784 130.143 106.139 120.956 107.519C125.745 114.126 128.422 117.838 130.007 127.015H136.274C135.448 119.721 136.842 115.611 145.326 108.215Z" 
        fill="url(#paint2_linear_51_3)" 
        stroke="black" 
        stroke-width="1.3926"
        />
        <path 
        d="M109.12 106.823C107.314 107.098 106.614 107.723 107.031 109.608C107.4 110.271 108.369 110.449 111.904 110.304V108.215C111.508 107.187 110.903 106.879 109.12 106.823Z" 
        fill="#470D0B" 
        stroke="black" 
        stroke-width="1.3926" 
        @click="showInfo('heart','Valve Aortique', 'Contrôle le passage du sang entre le ventricule gauche et l\'aorte.')"
        />
        <path 
        d="M77.0886 106.126L75.696 111C71.734 97.0102 68.2225 93.0109 59.6811 92.2002C51.244 92.6358 46.9595 94.8891 41.5774 108.911C36.8932 122.005 37.127 129.13 40.1848 141.637L45.7552 144.423C55.2017 146.252 57.6202 147.754 60.3774 150.689V153.474H55.5033C43.0512 154.719 42.9185 159.044 47.844 169.489C55.8937 182.131 61.9932 187.426 74.3034 195.252C86.9262 200.729 96.7953 201.799 117.474 201.519C128.821 203.401 131.745 203.003 130.007 199.43L111.904 182.023C91.7788 159.494 89.3519 154.845 89.622 150.689C91.7943 138.001 94.6595 130.667 102.155 117.267C97.1693 131.664 95.7694 139.011 98.6739 149.297L131.4 184.112C146.673 196.69 148.07 189.167 151.593 177.845V155.563C154.558 138.654 152.602 129.421 145.326 115.178C139.302 122.278 137.887 127.024 136.97 127.015C134.985 119.514 136.6 115.536 145.326 108.911C148.058 104.265 148.177 101.914 148.111 97.7706C145.054 89.1114 141.951 86.257 136.97 80.3631C142.434 82.0068 145.61 83.4122 152.289 90.1113C153.883 96.7898 154.456 101.842 154.378 115.178C161.9 125.526 166.01 131.892 169 166.008C168.565 185.585 170.148 198.334 158.556 207.089C150.732 211.501 149.442 217.859 138.763 218.927C125.77 215.921 95.9934 214.052 80.9706 211.964C65.9478 209.875 51.8279 197.762 45.7552 188.986C30.6619 174.654 28.2779 156.168 26.2588 119.356C30.9337 116.521 31.9832 114.821 32.5255 111.697L39.4885 99.1632C41.1402 96.4959 41.1299 94.9658 40.1848 92.2002C49.5965 83.4122 56.023 82.359 68.733 87.3261L76.3923 100.556L77.0886 106.126Z" 
        fill="#E3C398" 
        stroke="black" 
        stroke-width="1.3926"
        />
        <path 
        d="M61.0739 151.386C57.9277 146.756 54.1838 145.638 46.4517 144.423C49.9246 133.42 55.2384 129.811 74.9999 131.193C69.2813 140.652 69.7017 143.967 71.5184 149.297C64.3487 147.857 62.8892 148.918 61.0739 151.386Z" 
        fill="url(#paint3_linear_51_3)" 
        stroke="black" 
        stroke-width="1.3926"/>
        <path
        d="M67.3426 152.778H63.1648C62.5655 150.566 63.3113 150.048 65.95 149.993C67.2089 150.76 67.5216 151.358 67.3426 152.778Z" 
        fill="#656464" 
        stroke="black" 
        stroke-width="1.3926"
        @click="showInfo('heart','Valve Tricuspide', 'La valve tricuspide (valve atrio-ventriculaire) correspond à la valve du cœur qui crée une séparation entre le ventricule droit et l\'oreillette droite. Elle a pour rôle d\'empêcher que le sang ne reflue entre l\'oreillette droite et le ventricule droit.')"
        />
        <circle cx="65" cy="150" r="5" fill="yellow" stroke="black" stroke-width="1"
        @click="showInfo('heart','Valve Tricuspide', 'La valve tricuspide (valve atrio-ventriculaire) correspond à la valve du cœur qui crée une séparation entre le ventricule droit et l\'oreillette droite. Elle a pour rôle d\'empêcher que le sang ne reflue entre l\'oreillette droite et le ventricule droit.')"
        />
        @click="showInfo('heart','Veine Cave Supérieure', 'La veine cave supérieure est une veine large et courte qui transporte la majeure partie du sang désoxygéné de la partie du corps située au-dessus du diaphragme vers l\'atrium droit (anciennement oreillette droite) du cœur.')"
        <path
        d="M39.4903 134.674C41.7349 143.156 40.4354 141.177 45.757 143.726C51.2808 131.906 58.1161 129.658 75.0005 131.193C76.9816 126.783 76.4481 121.2 75.0005 110.304C70.5258 97.6613 67.1499 93.9874 59.6828 92.8965C41.099 93.4479 37.2457 126.193 39.4903 134.674Z"
        fill="url(#paint4_linear_51_3)"
        stroke="black"
        stroke-width="1.3926"
        @click="showInfo('heart','Oreillette Droite', 'Le rôle de l\'oreillette droite du cœur est de recevoir le sang veineux désoxygéné. Elle reçoit le sang provenant des veines caves supérieure et inférieure et l\'envoie au ventricule droit. La valvule tricuspide sépare l\'oreillette droite du ventricule droit et s\'ouvre pour permettre au sang de pénétrer dans le ventricule droit')"
        />
        <circle cx="60" cy="115" r="5" fill="yellow" stroke="black" stroke-width="1"
        @click="showInfo('heart','Oreillette Droite', 'Le rôle de l\'oreillette droite du cœur est de recevoir le sang veineux désoxygéné. Elle reçoit le sang provenant des veines caves supérieure et inférieure et l\'envoie au ventricule droit. La valvule tricuspide sépare l\'oreillette droite du ventricule droit et s\'ouvre pour permettre au sang de pénétrer dans le ventricule droit')"
        />
        <path
        d="M146.023 107.519C135.532 105.92 129.841 105.759 120.26 107.519L110.512 96.378C108.936 91.0335 111.465 88.373 118.171 83.8446C122.136 81.0778 127.052 80.6488 136.971 80.3631C145.978 90.9879 150.413 96.9424 146.023 107.519Z"
        fill="url(#paint5_linear_51_3)"
        stroke="black"
        stroke-width="1.3926"
        @click="showInfo('heart','Oreillette Gauche', 'L\'oreillette gauche joue un rôle important dans le remplissage ventriculaire gauche. Elle agit comme une “pompe contractile” qui fournit 15 à 30% du remplissage total du ventricule gauche, un “réservoir” qui collecte le retour veineux pulmonaire pendant la systole ventriculaire et un “conduit” permettant le passage du sang de l\’oreillette au ventricule gauche pendant la diastole ventriculaire précoce. Le sang oxygéné qui provient des poumons est conduit dans l\'oreillette gauche par les quatre veines pulmonaires')"
        />
        <circle cx="130" cy="95" r="5" fill="yellow" stroke="black" stroke-width="1"
        @click="showInfo('heart','Oreillette Gauche', 'L\'oreillette gauche joue un rôle important dans le remplissage ventriculaire gauche. Elle agit comme une “pompe contractile” qui fournit 15 à 30% du remplissage total du ventricule gauche, un “réservoir” qui collecte le retour veineux pulmonaire pendant la systole ventriculaire et un “conduit” permettant le passage du sang de l\’oreillette au ventricule gauche pendant la diastole ventriculaire précoce. Le sang oxygéné qui provient des poumons est conduit dans l\'oreillette gauche par les quatre veines pulmonaires')"
        />
        <path
        d="M77.7853 119.356C75.9952 114.685 75.9528 111.788 77.7853 106.126C88.2258 104.419 92.7637 105.203 97.978 110.304L99.3706 117.963C99.3874 120.475 100.113 122.043 92.4076 122.837C89.0401 122.396 88.3271 120.977 87.5335 117.963C84.9015 119.564 82.6303 119.741 77.7853 119.356Z"
        fill="url(#paint6_linear_51_3)"
        stroke="black"
        stroke-width="1.3926"
        @click="showInfo('heart','Valvule Sigmoïde', 'Une valve sigmoïde est une valve artérielle assurant la liaison entre un ventricule et les vaisseaux partant du cœur.')"
        />
        <circle cx="90" cy="112" r="5" fill="yellow" stroke="black" stroke-width="1"
        @click="showInfo('heart','Valvule Sigmoïde', 'Une valve sigmoïde est une valve artérielle assurant la liaison entre un ventricule et les vaisseaux partant du cœur.')"
        />
        <path d="M24.868 99.1632H38.794C38.1149 102.599 36.9053 104.228 33.9185 106.822H22.7791C20.8344 103.18 21.4095 101.531 24.868 99.1632Z" fill="#716173"/>
        <path d="M33.2222 111.697H23.474C20.6234 114.502 20.8556 116.006 22.0815 118.66H26.9556C30.8972 116.556 31.7145 114.803 33.2222 111.697Z" fill="#716173"/>
        <path
        d="M24.868 99.1632H38.794C38.1149 102.599 36.9053 104.228 33.9185 106.822H22.7791C20.8344 103.18 21.4095 101.531 24.868 99.1632Z"
        stroke="black"
        stroke-width="1.3926"
        @click="showInfo('heart','Veines Pulmonaires droite', 'Les quatre veines pulmonaires (une pour chaque lobe pulmonaire) sont des veines chargées de véhiculer le sang oxygéné jusqu\'aux poumons et jusqu\'au cœur, chargé de le propulser dans le reste de l\'organisme')"
        />
        <circle cx="25" cy="106" r="5" fill="yellow" stroke="black" stroke-width="1"
        @click="showInfo('heart','Veines Pulmonaires droite', 'Les quatre veines pulmonaires (une pour chaque lobe pulmonaire) sont des veines chargées de véhiculer le sang oxygéné jusqu\'aux poumons et jusqu\'au cœur, chargé de le propulser dans le reste de l\'organisme')"
        />
        <path
        d="M33.2222 111.697H23.474C20.6234 114.502 20.8556 116.006 22.0815 118.66H26.9556C30.8972 116.556 31.7145 114.803 33.2222 111.697Z"
        stroke="black"
        stroke-width="1.3926"
        @click="showInfo('heart','Veines Pulmonaires droite', 'Les quatre veines pulmonaires (une pour chaque lobe pulmonaire) sont des veines chargées de véhiculer le sang oxygéné jusqu\'aux poumons et jusqu\'au cœur, chargé de le propulser dans le reste de l\'organisme')"
        />
        <path 
        d="M101.46 113.785C95.3308 106.233 90.4448 104.115 77.7861 106.126L77.0898 101.252C89.0789 84.4475 95.3083 75.5564 93.801 73.4001L83.3565 66.4371L86.838 47.637L104.245 53.2074C114.44 55.6442 120.581 55.9695 132.794 54.6L157.164 50.4222L158.557 56.6889C149.546 57.4191 147.799 58.6619 147.416 61.563C148.902 65.5077 151.612 66.3839 158.557 66.4371V73.4001L141.149 71.3112C131.303 73.5525 127.365 75.2469 123.046 78.9705C106.631 92.3248 103.227 99.8503 101.46 113.785Z"
        fill="#CCB7BB"
        stroke="black"
        stroke-width="1.3926"
        @click="showInfo('heart','Artère pulmonaire', 'L\'artère pulmonaire droite est un vaisseau sanguin essentiel dans le corps humain, responsable de transporter le sang oxygéné du ventricule droit du cœur vers les poumons pour y subir un processus de réoxygénation.')"
        />
        <circle cx="107" cy="70" r="5" fill="yellow" stroke="black" stroke-width="1"
        @click="showInfo('heart','Artère pulmonaire', 'L\'artère pulmonaire droite est un vaisseau sanguin essentiel dans le corps humain, responsable de transporter le sang oxygéné du ventricule droit du cœur vers les poumons pour y subir un processus de réoxygénation.')"
        />
        <path d="M162.733 88.7187C159.201 90.0806 156.97 90.0985 152.985 90.1113C153.449 92.4323 154.377 97.2135 154.377 97.7706C157.368 95.4525 159.674 94.516 164.822 93.5928L162.733 88.7187Z" fill="#716173"/>
        <path d="M164.822 102.645C159.4 102.239 157.286 101.541 154.377 99.8595V108.215L165.518 107.519C163.631 105.824 163.884 104.704 164.822 102.645Z" fill="#716173"/>
        <path
        d="M162.733 88.7187C159.201 90.0806 156.97 90.0985 152.985 90.1113C153.449 92.4323 154.377 97.2135 154.377 97.7706C157.368 95.4525 159.674 94.516 164.822 93.5928L162.733 88.7187Z"
        stroke="black"
        stroke-width="1.3926"
        @click="showInfo('heart','Veines Pulmonaires gauche', 'Les quatre veines pulmonaires (une pour chaque lobe pulmonaire) sont des veines chargées de véhiculer le sang oxygéné jusqu\'aux poumons et jusqu\'au cœur, chargé de le propulser dans le reste de l\'organisme')"
        />
        <circle cx="160" cy="96" r="5" fill="yellow" stroke="black" stroke-width="1"
        @click="showInfo('heart','Veines Pulmonaires gauche', 'Les quatre veines pulmonaires (une pour chaque lobe pulmonaire) sont des veines chargées de véhiculer le sang oxygéné jusqu\'aux poumons et jusqu\'au cœur, chargé de le propulser dans le reste de l\'organisme')"
        />
        <path
        d="M164.822 102.645C159.4 102.239 157.286 101.541 154.377 99.8595V108.215L165.518 107.519C163.631 105.824 163.884 104.704 164.822 102.645Z"
        stroke="black"
        stroke-width="1.3926"
        @click="showInfo('heart','Veines Pulmonaires gauche', 'Les quatre veines pulmonaires (une pour chaque lobe pulmonaire) sont des veines chargées de véhiculer le sang oxygéné jusqu\'aux poumons et jusqu\'au cœur, chargé de le propulser dans le reste de l\'organisme')"
        />
        <path d="M61.0755 58.0816C58.2903 65.0446 65.0939 84.364 77.0904 100.556L93.8014 76.8817L91.0163 67.1335C90.2221 59.9221 91.4442 57.1429 95.8903 53.9038C101.211 50.7737 104.532 50.9642 111.905 54.6001L124.439 78.2743L136.276 78.9706L132.098 53.9038C129.802 45.3492 128.434 41.9915 125.831 39.9779L108.424 28.1408C105.694 26.5392 105.665 25.8625 105.639 24.6593V17.6963L104.246 17H99.3718L97.9792 17.6963V26.0519H94.4977L91.0163 17.6963L84.0533 19.7852V23.2667L87.5348 30.926L85.4459 33.7112H81.9644L75.0014 24.6593H72.9129L68.0385 28.1408V30.926C71.0429 34.0037 72.757 35.7049 72.9129 41.3705C71.52 46.9408 63.8607 51.1186 61.0755 58.0816Z" fill="#D3574E"/>
        <path d="M98.6755 246.082C99.692 222.133 98.5488 216.926 95.194 214.053L125.831 217.534C120.737 217.484 122.856 231.361 123.046 246.082C121.175 250.36 118.775 251.8 112.602 253.045C104.969 252.183 101.764 250.804 98.6755 246.082Z"
        fill="#D3574E"
        stroke="black"
        />
        <circle cx="110" cy="230" r="5" fill="yellow" stroke="black" stroke-width="1"
        @click="showInfo('heart','Aorte', 'L\'aorte est la plus grande et la principale artère du corps humain, partant du cœur, plus précisément du ventricule gauche. Elle a pour fonction de distribuer le sang oxygéné à l\'ensemble de l\'organisme, sauf à la circulation fonctionnelle des poumons. L\'aorte se divise en plusieurs parties, notamment l\'aorte thoracique et l\'aorte abdominale, et elle est essentielle pour le transport du sang vers les organes et les membres')"
        />
        <path 
        d="M61.0755 58.0816C58.2903 65.0446 65.0939 84.364 77.0904 100.556L93.8014 76.8817L91.0163 67.1335C90.2221 59.9221 91.4442 57.1429 95.8903 53.9038C101.211 50.7737 104.532 50.9642 111.905 54.6001L124.439 78.2743L136.276 78.9706L132.098 53.9038C129.802 45.3492 128.434 41.9915 125.831 39.9779L108.424 28.1408C105.694 26.5392 105.665 25.8625 105.639 24.6593V17.6963L104.246 17H99.3718L97.9792 17.6963V26.0519H94.4977L91.0163 17.6963L84.0533 19.7852V23.2667L87.5348 30.926L85.4459 33.7112H81.9644L75.0014 24.6593H72.9129L68.0385 28.1408V30.926C71.0429 34.0037 72.757 35.7049 72.9129 41.3705C71.52 46.9408 63.8607 51.1186 61.0755 58.0816Z" 
        stroke="black" 
        stroke-width="1.3926"
        @click="showInfo('heart','Aorte', 'L\'aorte est la plus grande et la principale artère du corps humain, partant du cœur, plus précisément du ventricule gauche. Elle a pour fonction de distribuer le sang oxygéné à l\'ensemble de l\'organisme, sauf à la circulation fonctionnelle des poumons. L\'aorte se divise en plusieurs parties, notamment l\'aorte thoracique et l\'aorte abdominale, et elle est essentielle pour le transport du sang vers les organes et les membres')"
        />
        <circle cx="80" cy="70" r="5" fill="yellow" stroke="black" stroke-width="1"
        @click="showInfo('heart','Aorte', 'L\'aorte est la plus grande et la principale artère du corps humain, partant du cœur, plus précisément du ventricule gauche. Elle a pour fonction de distribuer le sang oxygéné à l\'ensemble de l\'organisme, sauf à la circulation fonctionnelle des poumons. L\'aorte se divise en plusieurs parties, notamment l\'aorte thoracique et l\'aorte abdominale, et elle est essentielle pour le transport du sang vers les organes et les membres')"
        />
        <path
        d="M98.6755 246.082C99.692 222.133 98.5488 216.926 95.194 214.053L125.831 217.534C120.737 217.484 122.856 231.361 123.046 246.082C121.175 250.36 118.775 251.8 112.602 253.045C104.969 252.183 101.764 250.804 98.6755 246.082Z"
        stroke="black"
        stroke-width="1.3926"
        @click="showInfo('heart','Aorte', 'L\'aorte est la plus grande et la principale artère du corps humain, partant du cœur, plus précisément du ventricule gauche. Elle a pour fonction de distribuer le sang oxygéné à l\'ensemble de l\'organisme, sauf à la circulation fonctionnelle des poumons. L\'aorte se divise en plusieurs parties, notamment l\'aorte thoracique et l\'aorte abdominale, et elle est essentielle pour le transport du sang vers les organes et les membres')"
        />
        <path
        d="M36.7036 46.9407V51.1185C38.1883 56.1049 38.8519 59.3305 39.4888 66.4371L40.8814 91.5038C44.3557 88.8059 46.4954 87.2901 53.4148 84.5408C59.6261 84.498 63.0063 85.029 68.7333 87.326L63.163 78.2742C60.6183 72.5722 60.5806 69.6262 60.3778 64.3482C60.4717 58.4722 61.3091 56.1691 63.163 52.5111V46.9407L56.8963 43.4592H46.4518L36.7036 46.9407Z"
        fill="url(#paint7_linear_51_3)"
        stroke="black"
        stroke-width="1.3926"
        @click="showInfo('heart','Veine Cave Supérieure', 'La veine cave supérieure est une veine large et courte qui transporte la majeure partie du sang désoxygéné de la partie du corps située au-dessus du diaphragme vers l\'atrium droit (anciennement oreillette droite) du cœur.')"
        />
        <circle cx="53" cy="75" r="5" fill="yellow" stroke="black" stroke-width="1"
        @click="showInfo('heart','Veine Cave Supérieure', 'La veine cave supérieure est une veine large et courte qui transporte la majeure partie du sang désoxygéné de la partie du corps située au-dessus du diaphragme vers l\'atrium droit (anciennement oreillette droite) du cœur.')"
        />
        <path
        d="M35.3107 65.7409L19.9921 65.0446C18.5619 68.0357 18.7812 69.7127 19.9921 72.7039H32.5254C34.9933 75.1508 34.7945 76.5238 32.5254 78.9705H22.0809C20.1131 80.5139 19.7624 81.4546 19.2958 83.1483C19.161 85.2258 19.2274 86.3642 21.3847 88.0224L40.8811 85.2372L39.4885 64.3483L35.3107 65.7409Z"
        fill="#B790A7"
        stroke="black"
        stroke-width="1.3926"/>
        @click="showInfo('heart','Veine Pulmonaires droite', 'Les veines pulmonaires sont les veines qui transportent du sang riche en oxygène des poumons vers l\'atrium gauche (anciennement oreillette gauche) du cœur. Elles sont au nombre de quatre, soit deux pour chaque poumon. ')"
        <path
        d="M51.3258 233.549L46.4517 191.771C53.4487 200.918 59.202 205.139 73.6073 210.571L74.9999 232.156C73.6086 237.131 71.4804 239.05 64.5554 240.512C56.3255 238.611 53.3484 237.113 51.3258 233.549Z"
        fill="#89B7D3"
        stroke="black"
        stroke-width="1.3926"
        @click="showInfo('heart','Veine Cave Inférieure', 'La veine cave inférieure est une veine large située principalement dans l\'abdomen, issue de la réunion des deux veines iliaques communes et qui s\'ouvre dans l\'atrium droit (anciennement oreillette droite) du cœur.')"
        />
        <circle cx="65" cy="220" r="5" fill="yellow" stroke="black" stroke-width="1"
        @click="showInfo('heart','Veine Cave Inférieure', 'La veine cave inférieure est une veine large située principalement dans l\'abdomen, issue de la réunion des deux veines iliaques communes et qui s\'ouvre dans l\'atrium droit (anciennement oreillette droite) du cœur.')"
        />
        <path d="M47.1502 45.5481C41.7672 47.1079 39.3116 47.9972 40.1872 49.7259C41.4522 50.5336 43.3548 50.9904 48.5428 51.8148H54.1132C54.1132 51.8148 58.2902 51.1185 58.9873 49.0296C59.6844 46.9407 58.4922 46.1211 54.8095 45.5481C51.9181 45.197 50.2051 45.3226 47.1502 45.5481Z"
        fill="url(#paint8_linear_51_3)"
        stroke="black"
        stroke-width="1.3926"/>
        <circle cx="132" cy="130" r="5" fill="yellow" stroke="black" stroke-width="1"
        @click="showInfo('heart','Valve Mitrale','La valve mitrale est une des quatre valves du cœur qui permettent au sang de circuler dans la bonne direction. Elle est située entre l\'oreillette gauche et le ventricule gauche du cœur. La valve mitrale est également appelée valve atrio-ventriculaire gauche. Elle est constituée de deux cusps ou volets qui s\'ouvrent et se ferment une fois à chaque battement de cœur. Si la valve ne s\'ouvre ou ne se ferme pas correctement, la circulation sanguine peut être réduite')"
        />
        <defs>
        <linearGradient id="paint0_linear_51_3" x1="61.7707" y1="161.134" x2="116.082" y2="197.341" gradientUnits="userSpaceOnUse">
        <stop stop-color="#EDD2AC"/>
        <stop offset="0.472356" stop-color="#EDC89B"/>
        <stop offset="1" stop-color="#A2582C"/>
        </linearGradient>
        <linearGradient id="paint1_linear_51_3" x1="107.727" y1="111.697" x2="117.475" y2="163.919" gradientUnits="userSpaceOnUse">
        <stop stop-color="#A54F2A"/>
        <stop offset="0.376234" stop-color="#FDDA98"/>
        <stop offset="1" stop-color="#A66229"/>
        </linearGradient>
        <linearGradient id="paint2_linear_51_3" x1="133.141" y1="106.435" x2="133.141" y2="127.015" gradientUnits="userSpaceOnUse">
        <stop stop-color="#D8DEBD"/>
        <stop offset="1" stop-color="#F2EAC6"/>
        </linearGradient>
        <linearGradient id="paint3_linear_51_3" x1="71.5184" y1="133.282" x2="61.0739" y2="147.904" gradientUnits="userSpaceOnUse">
        <stop stop-color="#EFEDD7"/>
        <stop offset="1" stop-color="#DBD2AF"/>
        </linearGradient>
        <linearGradient id="paint4_linear_51_3" x1="57.605" y1="92.8965" x2="57.593" y2="128.408" gradientUnits="userSpaceOnUse">
        <stop stop-color="#927A62"/>
        <stop offset="1" stop-color="#CE9773"/>
        </linearGradient>
        <linearGradient id="paint5_linear_51_3" x1="128.896" y1="80.3631" x2="128.896" y2="107.519" gradientUnits="userSpaceOnUse">
        <stop stop-color="#9F6740"/>
        <stop offset="1" stop-color="#E6BA7F"/>
        </linearGradient>
        <linearGradient id="paint6_linear_51_3" x1="79.8743" y1="107.519" x2="95.8891" y2="117.963" gradientUnits="userSpaceOnUse">
        <stop offset="0.0593933" stop-color="#E2DAEA"/>
        <stop offset="1" stop-color="#514B63"/>
        </linearGradient>
        <linearGradient id="paint7_linear_51_3" x1="49.9333" y1="46.2444" x2="55.5037" y2="81.0594" gradientUnits="userSpaceOnUse">
        <stop stop-color="#6CA3D3"/>
        <stop offset="1" stop-color="#6BB6DF"/>
        </linearGradient>
        <linearGradient id="paint8_linear_51_3" x1="42.9716" y1="49.0296" x2="58.2902" y2="48.3333" gradientUnits="userSpaceOnUse">
        <stop stop-color="#4D7796"/>
        <stop offset="0.527149" stop-color="#5D9DCA"/>
        <stop offset="1" stop-color="#5385AA"/>
        </linearGradient>
        </defs>
    </svg>
    </div>
    <transition name="fade">
      <div class="info-container">
        <div class="title-container">
          <h3 v-if="selectedHeartPart" :class="{ 'active': selectedHeartPart }">{{ selectedHeartPart.name }}</h3>
        </div>
        <div class="text-container">
          <p v-if="selectedHeartPart" :class="{ 'active': selectedHeartPart }">
            {{ selectedHeartPart.description }}
          </p>
        </div>
      </div>
    </transition>
  </div>
  <div class="wrapper">
    <div class="body-container">
      <svg xmlns="http://www.w3.org/2000/svg" width="160" height="300" viewBox="0 0 160 300" fill="none">
<g clip-path="url(#clip0_62_13)">
<path d="M91.187 1.6667C73.1174 -1.21852 67.1743 -0.26385 60.4317 3.80355C57.744 5.74214 55.478 8.04206 53.9568 10.2141C47.3696 19.4891 47.2393 25.0752 49.6403 35.3221L58.2734 54.0195C58.2734 54.0195 57.1942 58.2932 57.1942 62.0327V70.5801C18.3453 79.6617 19.5711 82.2197 10.2518 94.6197C7.67966 103.269 8.41696 108.867 9.17266 118.659C5.117 123.571 4.75797 127.58 4.85612 135.22V157.123C1.36924 167.064 0.714435 172.356 0 181.696V247.405V251.144L4.85612 257.555L16.1871 263.431C18.3878 263.371 18.795 262.252 18.3453 258.623L11.3309 251.144V245.268H14.5683V252.212C16.2282 254.286 17.2365 255.087 19.964 252.212V245.268C19.3407 238.266 18.1181 234.772 14.5683 229.241V221.228L18.3453 210.544L26.4389 187.038C26.8902 173.723 27.1789 166.412 29.6763 161.93L32.3741 144.836L33.4532 187.038C30.8858 196.146 29.6593 201.288 28.0576 210.544L29.6763 281.06H69.6043L74.4604 247.405L80.3957 281.06H119.784L120.863 210.544C119.904 201.75 118.629 196.573 115.468 187.038L117.086 144.836L120.863 161.93C121.002 169.011 121.361 173.847 122.482 183.833C125.767 200.151 128.329 208.672 135.971 221.228V229.241C129.887 235.536 128.535 240.72 128.957 252.212C131.153 254.99 132.142 254.316 133.813 252.212L134.892 245.268H137.59V251.144L130.576 258.623C128.696 261.699 129.73 262.504 132.734 263.431C138.864 261.221 141.353 259.929 144.604 257.555C149.181 251.496 149.807 249.746 150 247.405V181.696C149.399 172.579 147.615 166.606 144.604 156.054L143.525 135.22C143.778 126.375 143.225 122.709 140.827 118.659L139.209 94.6197C139.209 85.0039 114.352 76.5828 93.8849 70.5801C92.6503 67.2421 93.0141 65.3708 93.8849 62.0327C104.401 61.7363 109.078 61.3722 108.993 59.3616C108.012 56.6998 108.217 55.6502 108.993 54.0195V50.28H110.612C110.967 45.6171 111.4 44.8344 112.23 43.8695C114.127 43.8695 117.086 45.4721 117.086 43.8695C117.086 42.2668 115.096 38.1068 112.23 35.3221C108.92 32.0258 109.224 30.6949 112.23 28.9115C111.616 22.727 110.86 19.6128 108.993 14.4878C110.984 13.075 110.877 12.1292 108.993 10.2141C103.278 5.59074 99.4486 3.69561 91.187 1.6667Z" fill="#FDD5B2" stroke="black" opacity=".2" stroke-width="2"/>
<path d="M61.5 220C58.024 222.186 56.8182 223.582 56.5 226.5C52.5626 226.337 52.1759 224.027 51 220.5L50 221C50.6663 225.951 51.7511 227.955 56 229C58.9727 237.535 61.8578 241.114 71.5 243L73 246H75.5L76.5 243C84.1786 241.308 87.9509 238.929 92.5 229L98.5 224L97.5 223C96 224.167 92.8 226.5 92 226.5C91.1119 222.438 89.8747 221.457 87.5 220C77.8109 220.961 72.1593 221.052 61.5 220Z" fill="url(#paint0_linear_62_13)" stroke="#F2A812"/>
<path d="M65.0215 183.472C68.3088 181.302 69.1228 180.268 70.0233 178.52C72.1979 176.628 73.594 177.492 76.1364 179.621L67.8 188.425C62.5399 189.144 52.4435 192.118 52.2392 192.826C51.1551 194.43 51.1526 195.553 51.6629 197.694C51.9005 197.041 55.7886 192.826 58.3522 192.826C61.131 192.826 61.9474 193.098 63.354 195.027C65.2465 192.872 66.3356 191.766 68.9116 191.726C71.7301 191.777 73.1288 192.273 74.4691 196.128C76.2437 192.948 77.2631 190.562 78.9151 190.625H83.3612C84.9802 193.554 85.8809 195.083 87.2515 195.027C88.4832 195.205 89.6767 193.843 92.2533 190.075H96.6993C98.857 189.882 99.4292 191.564 99.4781 197.228C99.4854 198.612 100.355 199.16 103.368 199.753C103.806 202.205 104.384 203.58 103.368 206.032C102.863 207.18 101.19 207.225 97.8108 207.133C97.4407 205.731 96.4522 205.385 93.3648 205.482C92.4887 207.638 92.164 209.003 92.2533 212.085L86.14 212.635C85.1569 212.661 84.6805 211.68 83.9169 208.783H82.2497C81.7434 211.755 81.1181 213.311 77.8036 215.386H73.9133C71.8782 209.239 71.2055 209.035 70.0233 208.783C68.6656 208.644 68.0154 209.38 67.2443 213.736H61.6867C60.4923 211.525 59.8651 210.085 58.3522 209.334C57.5189 208.697 56.5798 209.571 53.9062 213.736H45.5698V209.334H52.2392L53.3504 207.133C56.1389 202.655 57.404 200.983 58.3522 201.63C61.3062 203.268 62.3706 204.396 62.2425 207.133H65.0215C67.0339 203.67 68.1546 201.771 69.4673 202.18C72.8253 205.19 74.1472 206.791 74.4691 209.334C75.8926 210.698 76.7599 210.637 78.3594 209.334V204.932C79.8983 201.617 80.5824 198.329 82.2497 199.98C83.9169 201.63 86.1832 203.144 86.14 206.032L87.8072 204.381C88.0112 203.416 88.5355 202.673 90.0303 201.08C93.2861 200.616 94.2375 200.259 94.4763 199.429C93.2315 198.816 93.1503 198.121 93.3648 196.678C90.2447 197.957 89.3229 198.985 88.363 201.08H85.5842C83.8691 198.306 82.9111 196.583 81.1382 196.678C79.1698 196.317 78.6449 198.299 77.8036 202.18H72.2461C70.4491 198.013 69.7409 197.027 68.9116 197.228C67.5018 197.256 66.8002 198.796 65.577 202.18H61.6867C59.5877 200.925 59.4339 200.014 59.4637 198.329H57.2407C56.4322 201.161 55.5236 202.52 50.5716 203.281C47.034 202.715 46.4245 201.028 46.6816 196.678C46.6223 192.943 47.4072 190.958 52.2392 187.874C57.3132 185.892 60.2128 184.602 65.0215 183.472Z" fill="#FC726D" stroke="#E5786B" stroke-width="1.03"/>
<path d="M108.5 151.841C106.608 149.43 105.414 149.342 103 151.841C103 151.841 106.5 154.341 106.5 157.841C106.5 161.341 106 163.841 106 163.841C106 163.841 106.5 164.841 108 165.341C109.5 165.841 111.012 164.592 112 162.841C113.134 160.952 112.594 160.355 111.5 159.341C113.5 157.341 110.5 155.341 110.5 155.341C111.191 152.98 110.834 152.172 108.5 151.841Z" fill="url(#paint1_linear_62_13)" stroke="#DC26CC"/>
<path d="M50.5725 226.391H47.7937C47.8457 221.237 46.8045 219.662 43.9028 218.137H39.4568C36.6976 215.937 35.7032 213.841 35.0122 208.233C34.2955 200.682 35.4048 199.543 37.7901 198.329V196.128C35.0193 190.362 35.5641 187.528 41.6804 183.472C44.5146 181.939 46.4118 181.138 52.2397 180.171H59.4646C61.9855 180.384 63.2653 180.901 65.0221 183.472C65.742 180.648 67.4382 179.379 71.6912 177.42C75.1968 178.042 77.0041 178.546 77.8045 181.822H80.5833C82.5631 180.551 83.7334 179.864 89.4754 180.171C91.2861 180.054 92.272 180.518 93.9214 184.023H97.2559C97.6806 181.755 98.52 181.021 101.146 180.721C104.752 180.893 106.535 181.653 108.927 185.123V192.826C113.533 195.178 113.843 198.039 113.373 203.831C111.123 204.479 109.927 205.57 107.815 207.683C107.62 211.899 106.456 213.146 103.369 214.286C101.614 215.239 97.7872 215.155 97.2559 214.286C95.4319 213.182 94.4454 212.951 92.8099 214.286C92.3808 215.98 91.8262 216.795 90.5869 218.137C86.7384 219.283 84.2496 219.167 79.4718 218.137V225.29L77.2487 227.491V230.243C78.9133 231.088 79.3422 232.634 79.4718 236.78C80.1401 243.38 79.5334 248.185 74.4693 253.287C70.0458 248.368 69.5854 243.386 69.4682 236.78C69.63 235.08 70.0807 231.169 72.8027 230.243V227.491C70.7157 227.039 70.1124 226.491 69.4682 225.29C69.0125 221.491 69.4553 219.942 71.6912 218.137C73.1732 217.771 76.2484 217.037 76.693 217.037C76.9662 214.783 78.3661 214.054 80.5833 212.635C84.1502 211.209 86.2655 210.869 90.5869 212.635L92.2541 210.984L95.0329 207.683C99.0888 206.664 101.418 206.396 105.592 206.582V203.831C103.024 201.172 102.592 199.59 102.813 196.678L105.592 193.927V190.625L100.035 189.525L96.7002 187.324H93.9214L91.1426 189.525H85.0293L81.139 184.573H79.4718L75.5815 187.874H61.6876C56.8059 188.284 54.3114 187.885 50.0167 186.774C48.2103 190.551 46.3267 192.593 41.6804 196.128V198.329L45.5707 202.18C45.7993 206.98 45.5439 209.609 45.0149 214.286C46.1264 216.487 50.2597 218.013 50.5725 219.788V226.391Z" fill="#D4787E" stroke="#E5786B" stroke-width="1.03"/>
<path d="M71.1348 248.18L74.4137 253.375L78.3485 248.18C78.3485 248.18 77.6927 245.583 74.4137 245.583C71.1348 245.583 71.1348 248.18 71.1348 248.18Z" fill="#782C2C" stroke="#000B20" stroke-width="1.2154"/>
<path d="M83.9174 168.616L65.0218 169.166C62.0389 170.058 60.8352 171.375 58.9084 174.118C58.5576 176.271 59.1161 177.081 61.1315 177.97C69.9318 178.337 74.3145 177.873 80.5829 175.219C85.4989 172.316 85.9861 170.893 83.9174 168.616Z" fill="#F59516" stroke="#FC802E" stroke-width="1.03"/>
<path d="M91.6959 142.755C89.8289 145.658 85.0288 144.405 86.1384 147.157C87.248 149.908 85.8916 152.645 75.581 165.314C73.4669 166.989 71.9811 167.283 68.91 166.965C67.1192 171.698 66.2857 174.291 68.91 177.42C72.0514 177.35 73.8886 177.586 77.8021 180.171C87.8004 179.575 91.5483 177.679 96.6977 173.018C106.233 164.558 108.054 159.73 106.701 151.008C103.427 143.959 100.179 142.092 91.6959 142.755Z" fill="#FC766C" fill-opacity="0.53" stroke="#F48677" stroke-width="1.03"/>
<path d="M56.129 147.707H41.1236C36.4092 148.757 35.4893 150.477 35.0103 154.31V166.965C36.9089 175.27 38.1086 179.481 41.6793 182.372C46.9613 182.619 49.5211 182.434 51.6829 180.171C57.5058 174.241 60.9303 170.994 68.3556 165.865C72.055 165.564 73.8792 165.265 75.0246 163.664C80.9144 156.032 86.0996 150.034 85.584 148.257C84.8714 146.566 84.3007 145.735 82.2495 144.956L66.6883 142.755C61.1506 143.932 59.1078 145.161 56.129 147.707Z" fill="#C94C46" stroke="#CB6A5A" stroke-width="1.03"/>
<path d="M45.5698 161.065V164.367C49.1952 166.026 50.1013 166.111 54.4619 164.367C54.4619 164.367 55.0177 168.769 56.1292 169.869C57.2407 170.97 60.5752 172.07 60.5752 172.07L61.6867 169.869L60.0195 169.319C57.5158 167.5 57.5408 166.38 57.7964 164.367L60.5752 157.764C61.0517 155.362 60.5806 155.031 58.908 155.563L56.1292 161.616L52.7946 158.864C48.5716 158.4 46.9952 158.887 45.5698 161.065Z" fill="#2E5154" stroke="#975757" stroke-width="1.03"/>
<path d="M71.6904 142.755V39.8599C76.3511 40.0778 78.9747 40.1988 78.9153 40.9604L79.471 65.1709H78.3595C77.0356 63.249 75.9153 62.7902 73.3577 62.9699V66.2714L79.471 69.0226L80.5825 144.405L71.6904 142.755Z" fill="#FB776C" stroke="#F8BE99" stroke-width="1.03"/>
<path d="M102.257 44.2617C93.5733 41.8807 88.7092 42.091 80.0269 44.2617V53.0656C83.929 52.1657 86.2909 51.7021 92.8092 51.4149C98.6747 51.7178 101.23 52.1175 105.036 53.0656C107.613 52.6483 107.94 51.7634 107.815 49.7642C106.847 46.7833 105.58 45.6004 102.257 44.2617Z" fill="#D16069" stroke="#EA8078" stroke-width="1.03"/>
<path d="M62.7983 33.8073V40.9604C66.5086 43.1768 67.9368 42.8636 68.9116 38.7594C73.3293 38.5974 75.7667 38.5552 79.471 39.3097L83.3613 42.0608L86.1401 41.5106C81.6344 37.3478 79.2479 36.5383 75.025 35.458H68.9116C69.0154 33.9374 69.4164 32.995 71.1347 31.0561C71.9233 29.3542 70.9587 28.9332 68.9116 28.3049L62.7983 33.8073Z" fill="#F3931B"/>
<path d="M86.6958 55.2666C86.5523 53.7723 87.2671 53.2087 89.4746 52.5154H94.4764V55.8168H90.5861L86.1401 60.2187H88.3631C90.0626 60.2635 90.0483 61.2397 89.4746 63.5202C87.5501 64.4574 86.0293 64.6509 82.8055 64.6207C80.9629 63.4361 80.5716 62.1003 81.1383 58.568H85.5843L88.3631 55.8168L86.6958 55.2666Z" fill="#F3931B"/>
<path d="M62.7983 33.8073V40.9604C66.5086 43.1768 67.9368 42.8636 68.9116 38.7594C73.3293 38.5974 75.7667 38.5552 79.471 39.3097L83.3613 42.0608L86.1401 41.5106C81.6344 37.3478 79.2479 36.5383 75.025 35.458H68.9116C69.0154 33.9374 69.4164 32.995 71.1347 31.0561C71.9233 29.3542 70.9587 28.9332 68.9116 28.3049L62.7983 33.8073Z" stroke="#ECBB70" stroke-width="1.03"/>
<path d="M86.6958 55.2666C86.5523 53.7723 87.2671 53.2087 89.4746 52.5154H94.4764V55.8168H90.5861L86.1401 60.2187H88.3631C90.0626 60.2635 90.0483 61.2397 89.4746 63.5202C87.5501 64.4574 86.0293 64.6509 82.8055 64.6207C80.9629 63.4361 80.5716 62.1003 81.1383 58.568H85.5843L88.3631 55.8168L86.6958 55.2666Z" stroke="#ECBB70" stroke-width="1.03"/>
<path d="M86.2966 129.825L103.846 137.225C103.846 137.225 105.471 137.869 105.471 139.478V157.175H106.771L105.471 159.588L105.796 184.679C105.796 188.847 101.896 188.847 101.896 188.847H88.2465L77.8469 193.855H75.897V192.568L77.5219 192.247L75.897 191.925V190.959H79.7968L84.3466 188.847L81.4217 188.707L77.1969 190.316H75.897V189.458L77.5219 188.847H75.897V188.064H78.4969L80.4468 187.42L79.4718 186.777L77.8469 187.098L75.897 187.42V186.777L77.5219 186.133H75.897V185.168H78.4969L81.0968 186.133H84.6716L80.1218 183.881H77.8469L75.897 184.203V182.915H77.8469L75.897 182.272V180.985C75.897 180.985 77.1969 180.985 77.8469 181.307C78.4969 181.628 88.2465 186.133 88.2465 186.133H101.896C103.196 186.133 103.196 184.679 103.196 184.679V160.392L101.246 157.175H102.871V139.478L85.3216 132.077L86.2966 129.825Z" fill="#F90304"/>
<path d="M103.196 160.392L104.171 162.001L105.471 159.588M103.196 160.392L101.246 157.175H102.871V139.478L85.3216 132.077L86.2966 129.825L103.846 137.225C103.846 137.225 105.471 137.869 105.471 139.478V157.175H106.771L105.471 159.588M103.196 160.392V184.679C103.196 184.679 103.196 186.133 101.896 186.133H88.2465C88.2465 186.133 78.4969 181.628 77.8469 181.307C77.1969 180.985 75.897 180.985 75.897 180.985V182.272L77.8469 182.915H75.897V184.203L77.8469 183.881H80.1218L84.6716 186.133H81.0968L78.4969 185.168H75.897V186.133H77.5219L75.897 186.777V187.42L77.8469 187.098L79.4718 186.777L80.4468 187.42L78.4969 188.064H75.897V188.847H77.5219L75.897 189.458V190.316H77.1969L81.4217 188.707L84.3466 188.847L79.7968 190.959H75.897V191.925L77.5219 192.247L75.897 192.568V193.855H77.8469L88.2465 188.847H101.896C101.896 188.847 105.796 188.847 105.796 184.679L105.471 159.588" stroke="black" stroke-width="0.602309"/>
<path d="M65.5767 122.33L45.6733 114.702C45.6733 114.702 42.0984 112.772 42.0984 116.633V138.834V158.462L43.3984 157.198L41.1234 162H42.0984V186.011C42.0984 186.011 42.0984 188.711 45.0233 188.572L49.2481 188.711H62.8976L73.2971 193.695H75.2471V192.414L73.6221 192.094L75.2471 191.774V190.813H71.3472L66.7974 188.711L69.7223 188.572L73.9471 190.173H75.2471V189.319L73.6221 188.711H75.2471V187.932H72.6472L70.6973 187.292L71.6722 186.651L73.2971 186.972L75.2471 187.292V186.651L73.6221 186.011H75.2471V185.051H72.6472L70.0473 186.011H66.4724L71.0222 183.77H73.2971L75.2471 184.09V182.81H73.2971L75.2471 182.169V180.889C75.2471 180.889 73.9471 180.889 73.2971 181.209C72.6472 181.529 62.8976 186.011 62.8976 186.011H49.2481H45.0233V162H46.3232L43.3984 157.198L45.0233 158.462L44.3733 116.633L65.021 123.981L65.5767 122.33Z" fill="#0B0C82"/>
<path d="M42.0984 138.834V158.462L43.3984 157.198M42.0984 138.834C42.0984 137.709 42.0984 120.494 42.0984 116.633M42.0984 138.834V116.633M43.3984 157.198L45.0233 158.462L44.3733 116.633L65.021 123.981L65.5767 122.33L45.6733 114.702C45.6733 114.702 42.0984 112.772 42.0984 116.633M43.3984 157.198L46.3232 162H45.0233M43.3984 157.198L41.1234 162H42.0984M45.0233 162V186.011H49.2481H62.8976C62.8976 186.011 72.6472 181.529 73.2971 181.209C73.9471 180.889 75.2471 180.889 75.2471 180.889V182.169L73.2971 182.81H75.2471V184.09L73.2971 183.77H71.0222L66.4724 186.011H70.0473L72.6472 185.051H75.2471V186.011H73.6221L75.2471 186.651V187.292L73.2971 186.972L71.6722 186.651L70.6973 187.292L72.6472 187.932H75.2471V188.711H73.6221L75.2471 189.319V190.173H73.9471L69.7223 188.572L66.7974 188.711L71.3472 190.813H75.2471V191.774L73.6221 192.094L75.2471 192.414V193.695H73.2971L62.8976 188.711H49.2481L45.0233 188.572C42.0984 188.711 42.0984 186.011 42.0984 186.011V162M45.0233 162H42.0984" stroke="black" stroke-width="0.602309"/>
<path d="M79.1473 114.702C75.5724 114.059 72.0203 114.838 69.3977 116.633C66.6946 118.962 65.7874 119.907 65.4978 120.816C64.4853 125.964 64.6685 127.803 66.1478 129.503L70.6976 134.008C73.53 136.77 77.5223 138.191 79.7973 137.869C82.0722 137.547 85.3146 132.734 85.972 129.825C87.2562 122.645 82.7221 115.346 79.1473 114.702Z" fill="url(#paint2_linear_62_13)" stroke="black" stroke-width="0.602309"/>
<path d="M73.2971 119.529C72.5888 118.254 72.3221 117.276 70.6972 117.276C69.0723 117.276 67.2493 120.404 66.7974 122.424C66.8972 125.252 66.9368 126.867 68.7473 126.607C71.6554 126.238 72.922 125.807 74.597 124.677C74.7092 123.348 73.6221 123.39 73.6221 122.103C73.6221 120.816 73.6654 120.297 73.2971 119.529Z" fill="#01046E" stroke="black" stroke-width="0.602309"/>
<path d="M78.1721 124.998C77.4899 125.419 77.4505 125.721 77.5221 126.286C77.5221 126.286 80.1219 134.008 81.0968 134.651C82.0718 135.295 82.9186 132.823 83.3717 131.434C84.5191 125.881 85.0891 122.96 84.0217 123.39L78.1721 124.998Z" fill="#FA0102" stroke="black" stroke-width="0.602309"/>
<path d="M68.4234 128.538C67.7731 129.182 69.6881 130.348 70.0485 130.79C70.0485 130.79 76.3151 135.748 77.4862 135.788C78.6572 135.828 78.0657 133.285 77.7135 131.867C75.742 126.546 74.9228 126.607 72.9729 126.607C71.0231 126.607 69.0737 127.895 68.4234 128.538Z" fill="#01046E" stroke="black" stroke-width="0.602309"/>
<path d="M83.6965 122.103C82.8226 123.15 76.5468 124.033 76.5468 124.033L73.6219 118.242C72.8926 116.75 73.5256 116.166 75.5719 115.346C77.8066 115.307 78.9793 115.737 80.7716 117.276C83.5389 119.878 84.5704 121.055 83.6965 122.103Z" fill="#FA0102" stroke="black" stroke-width="0.602309"/>
<path d="M77.3823 77.2152H73.97C71.922 77.2152 73.312 86.9441 71.9231 85.9994C68.5002 81.5668 67.4773 81.0547 66.4628 81.9452C54.1395 91.5881 52.8129 109.649 53.4958 113.703C54.1788 117.757 56.5741 121.07 58.9556 120.46C63.9772 119.295 66.2013 117.836 69.1927 113.703C73.8398 106.152 73.3081 101.542 73.2875 93.4321C75.239 89.8136 76.4035 89.1919 78.7473 93.4321C79.6401 105.936 80.2869 111.38 82.1597 113.703C85.1409 118.19 92.3967 121.136 94.4442 120.46C96.4916 119.784 99.1057 108.917 98.539 105.595C90.8776 84.5417 87.9606 80.36 84.8895 81.9452C83.6786 82.8553 83.0443 83.4146 82.1597 84.648C80.7235 86.715 79.9442 87.2353 78.7473 84.6479C78.7476 80.2734 79.021 77.0654 77.3823 77.2152Z" fill="#82BEF3" stroke="#000B20" stroke-width="1.26485"/>
<path d="M76.5467 83.8131H78.4966L89.2212 88.6395H103.521C104.835 88.6989 105.499 88.8183 105.47 90.5701V97.6488H107.095L104.171 102.797L105.47 101.832V107.945C105.447 108.544 105.219 108.888 103.521 109.554L84.3464 118.563L82.7214 117.276L102.871 107.623V101.832L104.171 102.797L101.896 97.6488H103.196V90.5701H89.2212L78.4966 95.7182H76.5467V95.0747L77.8466 94.753V94.1094H76.2217V93.1442H78.8216L80.4465 93.4659L85.3213 90.8918H81.7465L78.1716 92.5006H76.2217V91.5353H78.1716L78.8216 90.8918H76.2217V89.9265H81.0965L79.7965 89.283H76.2217V88.3177H77.8466L76.2217 87.3525V86.3872L79.4715 87.0307L82.3964 88.3177H84.9963L81.4215 86.3872L76.2217 85.4219L77.8466 85.1001L76.5467 84.7784V83.8131Z" fill="#EF2124"/>
<path d="M75.572 83.8131H73.6221L62.8975 88.6395H48.5981C47.2838 88.6989 46.6197 88.8183 46.6482 90.5701L46.8106 100.062L45.6732 102.475H46.6482V107.945C46.6714 108.544 46.8999 108.888 48.5981 109.554L67.7723 118.563L69.3972 117.276L49.2481 107.623V102.475H50.548L49.2481 100.062L48.9231 90.5701H62.8975L73.6221 95.7182H75.572V95.0747L74.272 94.753V94.1094H75.897V93.1442H73.2971L71.6721 93.4659L66.7973 90.8918H70.3722L73.9471 92.5006H75.897V91.5353H73.9471L73.2971 90.8918H75.897V89.9265H71.0222L72.3221 89.283H75.897V88.3177H74.272L75.897 87.3525V86.3872L72.6471 87.0307L69.7222 88.3177H67.1223L70.6972 86.3872L75.897 85.4219L74.272 85.1001L75.572 84.7784V83.8131Z" fill="#0B0C82"/>
</g>
<defs>
<linearGradient id="paint0_linear_62_13" x1="58.5" y1="228.5" x2="91" y2="229.5" gradientUnits="userSpaceOnUse">
<stop stop-color="#F47901"/>
<stop offset="0.511821" stop-color="#F8AF08"/>
<stop offset="1" stop-color="#FC7A03"/>
</linearGradient>
<linearGradient id="paint1_linear_62_13" x1="107.815" y1="150" x2="107.815" y2="165.452" gradientUnits="userSpaceOnUse">
<stop stop-color="#DC26CC"/>
<stop offset="1" stop-color="#76146D"/>
</linearGradient>
<linearGradient id="paint2_linear_62_13" x1="75.5285" y1="114.479" x2="75.5285" y2="137.914" gradientUnits="userSpaceOnUse">
<stop stop-color="#EC3E40"/>
<stop offset="1" stop-color="#862324"/>
</linearGradient>
<clipPath id="clip0_62_13">
<rect width="160" height="300" fill="white"/>
</clipPath>
</defs>
    <circle cx="72" cy="155" r="5" fill="yellow" stroke="black" stroke-width="1"
          @click="showInfo('body','Foie', 'Décompose l\'alcool, les drogues et les autres toxines présentes dans le sang afin que ces substances puissent être évacuées du corps par les selles ou l\'urine')"
        /><!-- FOIE -->
        <circle cx="55" cy="164" r="4" fill="yellow" stroke="black" stroke-width="1"
          @click="showInfo('body','Vésicule Biliaire', 'La vésicule biliaire est une petite poche située sous le foie. Son rôle consiste à stocker la bile avant qu\'elle se déverse dans l\'intestin, ce qui arrive en particulier au moment de la digestion. Sécrétée par le foie, la bile est un liquide qui facilite la digestion des graisses.')"
        /><!-- VESICULE BILIAIRE -->
        <circle cx="95" cy="162" r="4" fill="yellow" stroke="black" stroke-width="1"
          @click="showInfo('body','Estomac', 'Organe long et tubulaire dans l\'abdomen qui reçoit la nourriture partiellement digérée de l\'estomac, absorbe les éléments nutritifs et rejette les aliments digérés dans le gros intestin.')"
        /><!-- ESTOMAC -->
        <circle cx="72" cy="173" r="4" fill="yellow" stroke="black" stroke-width="1"
          @click="showInfo('body','Pancreas', 'Pendant la digestion, le pancréas fabrique des sucs pancréatiques appelés enzymes. Ces enzymes décomposent les sucres, les graisses et les amidons. Le pancréas aide également le système digestif en produisant des hormones. Ce sont des messagers chimiques qui circulent dans le sang.')"
        /><!-- PANCREAS -->
        <circle cx="109" cy="159" r="3" fill="yellow" stroke="black" stroke-width="1"
          @click="showInfo('body','Ratte', 'Le rôle de la rate, longtemps méconnu, est extrêmement important. En effet, il s\'agit d\'un organe lymphoïde, c\'est-à-dire qu\'il stocke les lymphocytes et les monocytes, des cellules qui assurent la protection de l\'organisme (système immunitaire).')"
        /><!-- RATTE -->
        <circle cx="111" cy="156" r="2" fill="green" stroke="black" stroke-width="1"
          @click="showInfo('body','Hypochondre gauche', 'Sur l\'hypocondre gauche se projettent : la rate, l\'estomac et l\'angle gauche du côlon.')"
        /><!-- HYPOCHONDRE GAUCHE -->
        <circle cx="40" cy="210" r="4" fill="yellow" stroke="black" stroke-width="1"
          @click="showInfo('body','Gros intestin', 'La grande majorité des substances digestibles ont été absorbées dans l\'intestin grêle, seules l\'eau et les matières indigestes se retrouvent à l\'entrée du gros intestin. Son premier travail est de récupérer l\'eau qui reste dans ces matières indigestes, puis de compacter celles-ci sous la forme de selles.')"
        /><!-- GROS INSTESTIN -->
        <circle cx="69" cy="208" r="4" fill="yellow" stroke="black" stroke-width="1"
          @click="showInfo('body','Intestin grêle', 'Ces régions de l\'intestin grêle participent largement à l\'absorption des graisses et autres nutriments. Les mouvements digestifs facilitent l\'absorption, elle-même renforcée par la grande surface de contact formée par les replis, villosités et microvillosités.')"
        /><!-- INSTESTIN GRELE -->
        <circle cx="75" cy="250" r="2" fill="yellow" stroke="black" stroke-width="1"
          @click="showInfo('body','Rectum', 'Le rectum est un lieu de rétention des selles . Lorsqu\'il est plein, il expulse les selles hors du corps par l\'anus.')"
        /><!-- RECTUM -->
        <circle cx="67" cy="228" r="3" fill="yellow" stroke="black" stroke-width="1"
          @click="showInfo('body','Vessie', 'Sert à emmagasiner l\'urine avant qu\'elle ne soit évacuée du corps. La vessie a une paroi élastique, ce qui lui permet de grossir (se dilater) à mesure qu\'elle se remplit d\'urine, et de rétrécir (se contracter) lorsqu\'elle se vide.')"
        /><!-- VESSIE -->
        <circle cx="50" cy="227" r="3" fill="yellow" stroke="black" stroke-width="1"
          @click="showInfo('body','Appendice', 'Le rôle de l\'appendice n\'est pas totalement élucidé, mais il pourrait intervenir dans le système immunitaire. L\'appendice abriterait une flore bactérienne bénéfique qui serait tenue en réserve pour répondre à une indigestion grave. Elle peut parfois mener à une inflammation (appendicite) nécessitant son ablation (appendicectomie)')"
        /><!-- APPENDICE -->
        <circle cx="65" cy="104" r="3" fill="yellow" stroke="black" stroke-width="1"
          @click="showInfo('body','Poumons', 'Les principales fonctions des poumons sont de transférer dans le sang l\'oxygène présent dans l\'air et d\'évacuer dans l\'air le dioxyde de carbone présent dans le sang. L\'air entre par la bouche ou le nez et descend dans la trachée, les bronches et les bronchioles jusqu\'aux alvéoles.')"
        /><!-- POUMONS -->
        <circle cx="76" cy="53" r="3" fill="yellow" stroke="black" stroke-width="1"
          @click="showInfo('body','Œsophage', 'L\'œsophage est le premier segment du tube digestif qui a pour fonction le transport des aliments mâchés. Ce tube musculeux s\'étend du larynx jusqu\'à l\'estomac, où la nourriture est digérée. La digestion commence de manière mécanique, par la contracture des muscles de l\'estomac.')"
        /><!-- OEUSOPHAGE -->
        <circle cx="76" cy="66" r="2" fill="yellow" stroke="black" stroke-width="1"
          @click="showInfo('body','Clapet', 'Le sphincter inférieur de l\'œsophage est un muscle situé entre l\'œsophage et l\'estomac. Il permet d\'ouvrir et de fermer l\'entrée dans l\'estomac. Chez de nombreuses personnes il peut disfonctionner, menant à des remontées acides et une sensation d\'inconfort plus ou moins intense.')"
        /><!-- CLAPET -->
        <circle cx="94" cy="47" r="3" fill="yellow" stroke="black" stroke-width="1"
          @click="showInfo('body','Langue', 'La langue, organe important de la cavité buccale, sert tant à la déglutition, qu\'à la mastication, à la gustation et au langage.')"
        /><!-- LANGUE -->
        <circle cx="66" cy="37" r="2" fill="yellow" stroke="black" stroke-width="1"
          @click="showInfo('body','Glandes salivaires', 'Les glandes salivaires jouent un rôle important dans la digestion puisqu\'elles produisent de la salive. La salive aide à humidifier la nourriture afin qu\'on puisse l\'avaler plus facilement. Elle contient aussi une enzyme appelée amylase qui aide l\'estomac à décomposer plus facilement l\'amidon provenant des aliments.')"
        /><!-- GLANDES SALIVAIRES -->
        <circle cx="117" cy="210" r="2" fill="green" stroke="black" stroke-width="1"
          @click="showInfo('body','Flanc gauche', 'Zone du colon descendant')"
        /><!-- FLANC GAUCHE -->
        <circle cx="32" cy="210" r="2" fill="green" stroke="black" stroke-width="1"
          @click="showInfo('body','Flanc droit', 'Zone du colon ascendant')"
        /><!-- FLANC DROIT -->
        <circle cx="50" cy="180" r="2" fill="green" stroke="black" stroke-width="1"
          @click="showInfo('body','Hypochondre droit', 'Zone regroupant le foie, la vésicule biliaire et le duodénum (première partie de l\'intestin grêle)')"
        /><!-- HYPOCHONDRE DROIT -->
        <circle cx="88" cy="172" r="2" fill="green" stroke="black" stroke-width="1"
          @click="showInfo('body','Epigastre', 'Organe musculaire creux situé dans l\'abdomen qui reçoit la nourriture qui passe par l\'oesophage. L\'estomac secrète des sucs digestifs qui sont mélangés à la nourriture afin de la transformer en un liquide clair qui, ensuite, est expulsé vers le duodénum')"
        /><!-- EPIGASTRE -->
        <circle cx="84" cy="248" r="2" fill="green" stroke="black" stroke-width="1"
          @click="showInfo('body','Fosse iliaque gauche', 'La fosse iliaque gauche est occupée essentiellement par les côlons descendant et sigmoïde et par les l\'ovaire gauche chez la femme')"
        /><!-- FOSSE ILIAQUE GAUCHE -->
        <circle cx="64" cy="248" r="2" fill="green" stroke="black" stroke-width="1"
          @click="showInfo('body','Fosse iliaque droite', 'La fosse iliaque droite est occupée essentiellement par le Caecum (Première partie du côlon, et constitue un organe appartenant au système digestif de la plupart des mammifères), l\'appendice et l\'ovaire droit chez la femme')"
        /><!-- FOSSE ILIAQUE DROITE -->
        <circle cx="88" cy="172" r="2" fill="green" stroke="black" stroke-width="1"
          @click="showInfo('body','Hypogastre', 'Zone regroupant la vessie et l\'utérus chez la femme')"
        /><!-- HYPOGASTRE -->
</svg>
    </div>
    <transition name="fade">
      <div class="info-container">
        <div class="title-container">
          <h3 v-if="selectedBodyPart" :class="{ 'active': selectedBodyPart }">{{ selectedBodyPart.name }}</h3>
        </div>
        <div class="text-container">
          <p v-if="selectedBodyPart" :class="{ 'active': selectedBodyPart }">
            {{ selectedBodyPart.description }}
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
      selectedHeartPart: null,  // Stores selected part info for heart
      selectedBodyPart: null,    // Stores selected part info for body
    };
  },
  methods: {
    showInfo(section, name, description) {
      if (section === 'heart') {
        this.selectedHeartPart = { name, description };
        this.selectedBodyPart = null; // Reset body info when heart is clicked
      } else if (section === 'body') {
        this.selectedBodyPart = { name, description };
        this.selectedHeartPart = null; // Reset heart info when body is clicked
      }
    }
  }
};
  </script>
  
  <style scoped>
  @keyframes appear {
    100% {
      opacity: 1;
      left: 0;
    }
  }
  
.fade-enter-active, .fade-leave-active {
  transition: opacity 0.6s ease, transform 0.6s ease;
}
.fade-enter-from, .fade-leave-to {
  opacity: 0;
  transform: translateY(10px);
}

.active {
  opacity: 1;
  animation: appear .2s ease-in-out forwards;
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
  transition: .2s ease-in-out;

  &:hover {
    r: 7px;
    fill: rgb(255, 0, 0);
  }
}

.wrapper {
  height: auto;
  display: grid;
  grid-template-columns: 1fr 1fr;
  grid-template-rows: 1fr;
  width: 98%;
  margin: 50px auto;
  
  .heart-container {
    width: 100%;
    height: auto;
    margin: 0 auto;
  }

  .body-container {
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
        animation: appear .2s ease-in-out forwards;
        left: 50%;
        position: relative;
        animation: appear .2s ease-in-out forwards;
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
        animation: appear .4s ease-in-out forwards;
        height: 100%;
      }
    }
  }
}

@media (min-width:320px) and (max-width:991px) {
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
