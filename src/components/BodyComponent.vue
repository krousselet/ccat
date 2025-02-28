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
          <circle cx="65" cy="165" r="5" fill="red" stroke="black" stroke-width="1"
          @click="showInfo('heart', 'Ventricule droit', 'Le ventricule droit est une cavité musculaire inférieure...')"
        />
          <path
            d="M109.815 110.304C104.952 110.506 103.729 111.549 102.156 113.785C102.344 121.972 101.615 126.423 97.9782 133.978C96.9966 140.152 97.0507 143.52 98.6745 149.297L120.26 172.274C120.239 168.056 120.65 166.613 121.652 164.615C120.777 156.121 121.446 154.073 123.045 151.386C128.631 142.382 127.568 138.174 126.526 130.497C123.731 113.924 118.897 112.235 109.815 110.304Z"
            fill="url(#paint1_linear_51_3)"
            stroke="black"
            stroke-width="1.3926"
          />
          <circle cx="113" cy="125" r="5" fill="red" stroke="black" stroke-width="1"
          @click="showInfo('heart','Ventricule gauche', 'Le ventricule gauche est la cavité du cœur...')"
        />
          <path
            d="M145.326 108.215C135.375 105.784 130.143 106.139 120.956 107.519C125.745 114.126 128.422 117.838 130.007 127.015H136.274C135.448 119.721 136.842 115.611 145.326 108.215Z"
            fill="url(#paint2_linear_51_3)"
            stroke="black"
            stroke-width="1.3926"
            @click="showInfo('heart','Valve aortique', 'La valve aortique contrôle le passage du sang entre le ventricule gauche et l\'aorte.')"
          />
          <circle cx="110" cy="109" r="5" fill="red" stroke="black" stroke-width="1"
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
        <circle cx="65" cy="150" r="5" fill="red" stroke="black" stroke-width="1"
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
        <circle cx="60" cy="115" r="5" fill="red" stroke="black" stroke-width="1"
        @click="showInfo('heart','Oreillette Gauche', 'L\'oreillette gauche joue un rôle important dans le remplissage ventriculaire gauche. Elle agit comme une “pompe contractile” qui fournit 15 à 30% du remplissage total du ventricule gauche, un “réservoir” qui collecte le retour veineux pulmonaire pendant la systole ventriculaire et un “conduit” permettant le passage du sang de l\’oreillette au ventricule gauche pendant la diastole ventriculaire précoce. Le sang oxygéné qui provient des poumons est conduit dans l\'oreillette gauche par les quatre veines pulmonaires')"
        />
        <path
        d="M146.023 107.519C135.532 105.92 129.841 105.759 120.26 107.519L110.512 96.378C108.936 91.0335 111.465 88.373 118.171 83.8446C122.136 81.0778 127.052 80.6488 136.971 80.3631C145.978 90.9879 150.413 96.9424 146.023 107.519Z"
        fill="url(#paint5_linear_51_3)"
        stroke="black"
        stroke-width="1.3926"
        @click="showInfo('heart','Oreillette Gauche', 'L\'oreillette gauche joue un rôle important dans le remplissage ventriculaire gauche. Elle agit comme une “pompe contractile” qui fournit 15 à 30% du remplissage total du ventricule gauche, un “réservoir” qui collecte le retour veineux pulmonaire pendant la systole ventriculaire et un “conduit” permettant le passage du sang de l\’oreillette au ventricule gauche pendant la diastole ventriculaire précoce. Le sang oxygéné qui provient des poumons est conduit dans l\'oreillette gauche par les quatre veines pulmonaires')"
        />
        <circle cx="130" cy="95" r="5" fill="red" stroke="black" stroke-width="1"
        @click="showInfo('heart','Oreillette Gauche', 'L\'oreillette gauche joue un rôle important dans le remplissage ventriculaire gauche. Elle agit comme une “pompe contractile” qui fournit 15 à 30% du remplissage total du ventricule gauche, un “réservoir” qui collecte le retour veineux pulmonaire pendant la systole ventriculaire et un “conduit” permettant le passage du sang de l\’oreillette au ventricule gauche pendant la diastole ventriculaire précoce. Le sang oxygéné qui provient des poumons est conduit dans l\'oreillette gauche par les quatre veines pulmonaires')"
        />
        <path
        d="M77.7853 119.356C75.9952 114.685 75.9528 111.788 77.7853 106.126C88.2258 104.419 92.7637 105.203 97.978 110.304L99.3706 117.963C99.3874 120.475 100.113 122.043 92.4076 122.837C89.0401 122.396 88.3271 120.977 87.5335 117.963C84.9015 119.564 82.6303 119.741 77.7853 119.356Z"
        fill="url(#paint6_linear_51_3)"
        stroke="black"
        stroke-width="1.3926"
        @click="showInfo('heart','Valvule Sigmoïde', 'Une valve sigmoïde est une valve artérielle assurant la liaison entre un ventricule et les vaisseaux partant du cœur.')"
        />
        <circle cx="90" cy="112" r="5" fill="red" stroke="black" stroke-width="1"
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
        <circle cx="25" cy="106" r="5" fill="red" stroke="black" stroke-width="1"
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
        <circle cx="107" cy="70" r="5" fill="red" stroke="black" stroke-width="1"
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
        <circle cx="160" cy="96" r="5" fill="red" stroke="black" stroke-width="1"
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
        <circle cx="110" cy="230" r="5" fill="red" stroke="black" stroke-width="1"
        @click="showInfo('heart','Aorte', 'L\'aorte est la plus grande et la principale artère du corps humain, partant du cœur, plus précisément du ventricule gauche. Elle a pour fonction de distribuer le sang oxygéné à l\'ensemble de l\'organisme, sauf à la circulation fonctionnelle des poumons. L\'aorte se divise en plusieurs parties, notamment l\'aorte thoracique et l\'aorte abdominale, et elle est essentielle pour le transport du sang vers les organes et les membres')"
        />
        <path 
        d="M61.0755 58.0816C58.2903 65.0446 65.0939 84.364 77.0904 100.556L93.8014 76.8817L91.0163 67.1335C90.2221 59.9221 91.4442 57.1429 95.8903 53.9038C101.211 50.7737 104.532 50.9642 111.905 54.6001L124.439 78.2743L136.276 78.9706L132.098 53.9038C129.802 45.3492 128.434 41.9915 125.831 39.9779L108.424 28.1408C105.694 26.5392 105.665 25.8625 105.639 24.6593V17.6963L104.246 17H99.3718L97.9792 17.6963V26.0519H94.4977L91.0163 17.6963L84.0533 19.7852V23.2667L87.5348 30.926L85.4459 33.7112H81.9644L75.0014 24.6593H72.9129L68.0385 28.1408V30.926C71.0429 34.0037 72.757 35.7049 72.9129 41.3705C71.52 46.9408 63.8607 51.1186 61.0755 58.0816Z" 
        stroke="black" 
        stroke-width="1.3926"
        @click="showInfo('heart','Aorte', 'L\'aorte est la plus grande et la principale artère du corps humain, partant du cœur, plus précisément du ventricule gauche. Elle a pour fonction de distribuer le sang oxygéné à l\'ensemble de l\'organisme, sauf à la circulation fonctionnelle des poumons. L\'aorte se divise en plusieurs parties, notamment l\'aorte thoracique et l\'aorte abdominale, et elle est essentielle pour le transport du sang vers les organes et les membres')"
        />
        <circle cx="80" cy="70" r="5" fill="red" stroke="black" stroke-width="1"
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
        <circle cx="53" cy="75" r="5" fill="red" stroke="black" stroke-width="1"
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
        <circle cx="65" cy="220" r="5" fill="red" stroke="black" stroke-width="1"
        @click="showInfo('heart','Veine Cave Inférieure', 'La veine cave inférieure est une veine large située principalement dans l\'abdomen, issue de la réunion des deux veines iliaques communes et qui s\'ouvre dans l\'atrium droit (anciennement oreillette droite) du cœur.')"
        />
        <path d="M47.1502 45.5481C41.7672 47.1079 39.3116 47.9972 40.1872 49.7259C41.4522 50.5336 43.3548 50.9904 48.5428 51.8148H54.1132C54.1132 51.8148 58.2902 51.1185 58.9873 49.0296C59.6844 46.9407 58.4922 46.1211 54.8095 45.5481C51.9181 45.197 50.2051 45.3226 47.1502 45.5481Z"
        fill="url(#paint8_linear_51_3)"
        stroke="black"
        stroke-width="1.3926"/>
        <circle cx="132" cy="130" r="5" fill="red" stroke="black" stroke-width="1"
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
          <h3 v-if="selectedHeartPart">{{ selectedHeartPart.name }}</h3>
        </div>
        <div class="text-container">
          <p v-if="selectedHeartPart">
            {{ selectedHeartPart.description }}
          </p>
        </div>
      </div>
    </transition>
  </div>
  <div class="wrapper">
    <div class="body-container">
      <svg xmlns="http://www.w3.org/2000/svg" width="160" height="300" viewBox="0 0 160 300" fill="none">
        <path d="M95.5 19.56C78.7555 16.8595 73.2482 17.753 67 21.56C64.5094 23.3744 62.4096 25.527 61 27.5599C54.8958 36.241 54.775 41.4693 57 51.0599L65 68.5599C65 68.5599 64 72.5599 64 76.0599V84.0599C28 92.5599 29.1359 94.9541 20.5 106.56C18.1165 114.656 18.7997 119.895 19.5 129.06C15.7418 133.657 15.4091 137.41 15.5 144.56V165.06C12.2688 174.365 11.662 179.318 11 188.06V249.56V253.06L15.5 259.06L26 264.56C28.0394 264.504 28.4167 263.456 28 260.06L21.5 253.06V247.56H24.5V254.06C26.0382 256.001 26.9725 256.751 29.5 254.06V247.56C28.9223 241.007 27.7895 237.737 24.5 232.56V225.06L28 215.06L35.5 193.06C35.9183 180.598 36.1858 173.755 38.5 169.56L41 153.56L42 193.06C39.6208 201.584 38.4843 206.396 37 215.06L38.5 281.06H75.5L80 249.56L85.5 281.06H122L123 215.06C122.111 206.829 120.929 201.984 118 193.06L119.5 153.56L123 169.56C123.129 176.187 123.461 180.713 124.5 190.06C127.544 205.333 129.919 213.308 137 225.06V232.56C131.362 238.452 130.109 243.303 130.5 254.06C132.535 256.66 133.452 256.028 135 254.06L136 247.56H138.5V253.06L132 260.06C130.258 262.939 131.216 263.693 134 264.56C139.68 262.492 141.987 261.282 145 259.06C149.241 253.389 149.821 251.752 150 249.56V188.06C149.443 179.527 147.79 173.936 145 164.06L144 144.56C144.235 136.281 143.722 132.85 141.5 129.06L140 106.56C140 97.5599 116.966 89.6782 98 84.0599C96.8559 80.9357 97.1931 79.1842 98 76.0599C107.745 75.7825 112.079 75.4417 112 73.5599C111.091 71.0686 111.282 70.0861 112 68.5599V65.0599H113.5C113.83 60.6956 114.231 59.9631 115 59.0599C116.757 59.0599 119.5 60.5599 119.5 59.0599C119.5 57.5599 117.655 53.6663 115 51.0599C111.933 47.9747 112.214 46.7291 115 45.0599C114.431 39.2715 113.73 36.3567 112 31.5599C113.845 30.2376 113.746 29.3524 112 27.5599C106.705 23.2327 103.156 21.4589 95.5 19.56Z" fill="#FDD5B2" stroke="black"/>
        <path 
        d="M71.5002 188.56C74.4577 186.588 75.1901 185.648 76.0002 184.06C77.9566 182.341 79.2127 183.126 81.5 185.06L74 193.06C69.2675 193.714 60.184 196.416 60.0002 197.06C59.0249 198.517 59.0227 199.538 59.4818 201.483C59.6956 200.89 63.1936 197.06 65.5 197.06C68 197.06 68.7345 197.307 70 199.06C71.7026 197.101 72.6825 196.096 75 196.06C77.5358 196.106 78.7941 196.557 80 200.06C81.5965 197.17 82.5137 195.002 84 195.06H88C89.4566 197.721 90.2669 199.11 91.5 199.06C92.6081 199.221 93.6819 197.984 96 194.56H100C101.941 194.384 102.456 195.912 102.5 201.06C102.507 202.317 103.289 202.815 106 203.354C106.394 205.582 106.914 206.832 106 209.06C105.546 210.103 104.04 210.144 101 210.06C100.667 208.786 99.7776 208.472 97 208.56C96.2118 210.519 95.9197 211.759 96 214.56L90.5 215.06C89.6155 215.084 89.1869 214.192 88.5 211.56H87C86.5445 214.26 85.9819 215.675 83 217.56H79.5C77.669 211.974 77.0638 211.789 76.0002 211.56C74.7787 211.433 74.1937 212.102 73.5 216.06H68.5C67.4254 214.052 66.8611 212.743 65.5 212.06C64.7503 211.482 63.9054 212.276 61.5 216.06H54V212.06H60.0002L61 210.06C63.5088 205.991 64.6469 204.472 65.5 205.06C68.1576 206.548 69.1153 207.573 69 210.06H71.5002C73.3107 206.913 74.319 205.188 75.5 205.56C78.5211 208.295 79.7104 209.749 80 212.06C81.2806 213.3 82.0609 213.245 83.5 212.06V208.06C84.8845 205.048 85.5 202.06 87 203.56C88.5 205.06 90.5389 206.436 90.5 209.06L92 207.56C92.1835 206.682 92.6552 206.007 94 204.56C96.9292 204.138 97.7852 203.814 98 203.06C96.8801 202.503 96.807 201.871 97 200.56C94.1929 201.722 93.3636 202.656 92.5 204.56H90C88.457 202.04 87.5951 200.473 86 200.56C84.2291 200.232 83.7569 202.033 83 205.56H78C76.3833 201.773 75.7461 200.877 75 201.06C73.7317 201.085 73.1005 202.485 72 205.56H68.5C66.6115 204.419 66.4732 203.592 66.5 202.06H64.5C63.7726 204.633 62.9552 205.868 58.5 206.56C55.3172 206.046 54.7689 204.513 55.0002 200.56C54.9469 197.166 55.653 195.362 60.0002 192.56C64.5652 190.759 67.174 189.586 71.5002 188.56Z"
        fill="#FC726D" 
        stroke="#E5786B"
        />
        <path d="M58.5006 227.56H56.0006C56.0474 222.876 55.1106 221.445 52.5 220.06H48.5C46.0177 218.061 45.123 216.156 44.5013 211.06C43.8565 204.198 44.8546 203.163 47.0006 202.06V200.06C44.5077 194.82 44.9978 192.246 50.5006 188.56C53.0505 187.167 54.7573 186.439 60.0006 185.56H66.5006C68.7686 185.754 69.92 186.223 71.5006 188.56C72.1482 185.994 73.6743 184.84 77.5006 183.06C80.6545 183.626 82.2805 184.084 83.0006 187.06H85.5006C87.2818 185.905 88.3347 185.281 93.5006 185.56C95.1296 185.454 96.0166 185.875 97.5006 189.06H100.501C100.883 187 101.638 186.333 104.001 186.06C107.244 186.216 108.848 186.907 111.001 190.06V197.06C115.145 199.197 115.423 201.797 115.001 207.06C112.977 207.648 111.901 208.64 110.001 210.56C109.825 214.391 108.777 215.524 106.001 216.56C104.422 217.427 100.979 217.35 100.501 216.56C98.8595 215.557 97.972 215.347 96.5006 216.56C96.1145 218.099 95.6156 218.841 94.5006 220.06C91.0382 221.101 88.7991 220.995 84.5006 220.06V226.56L82.5006 228.56V231.06C83.9981 231.828 84.384 233.233 84.5006 237C85.1018 242.998 84.556 247.364 80 252C76.0203 247.53 75.606 243.004 75.5006 237C75.6462 235.456 76.0517 231.901 78.5006 231.06V228.56C76.623 228.149 76.0802 227.651 75.5006 226.56C75.0906 223.108 75.489 221.7 77.5006 220.06C78.8339 219.727 81.6006 219.06 82.0006 219.06C82.2464 217.012 83.5059 216.35 85.5006 215.06C88.7096 213.765 90.6127 213.456 94.5006 215.06L96.0006 213.56L98.5006 210.56C102.15 209.635 104.245 209.39 108.001 209.56V207.06C105.69 204.644 105.302 203.206 105.501 200.56L108.001 198.06V195.06L103.001 194.06L100.001 192.06H97.5006L95.0006 194.06H89.5006L86.0006 189.56H84.5006L81.0006 192.56H68.5006C64.1086 192.932 61.8643 192.57 58.0006 191.56C56.3753 194.992 54.6808 196.848 50.5006 200.06V202.06L54.0006 205.56C54.2062 209.921 53.9764 212.31 53.5006 216.56C54.5006 218.56 58.2192 219.947 58.5006 221.56V227.56Z" fill="#D4787E" stroke="#E5786B"/>
        <path d="M77 247.36L79.95 252.08L83.49 247.36C83.49 247.36 82.9 245 79.95 245C77 245 77 247.36 77 247.36Z" fill="#782C2C" stroke="#000B20" stroke-width="1.18"/>
        <path d="M88.5002 175.06L71.5002 175.56C68.8166 176.371 67.7336 177.567 66.0002 180.06C65.6845 182.016 66.187 182.752 68.0002 183.56C75.9176 183.894 79.8606 183.472 85.5002 181.06C89.923 178.423 90.3613 177.129 88.5002 175.06Z" fill="#F59516" stroke="#FC802E"/>
        <path d="M95.4983 151.56C93.8186 154.198 89.5 153.06 90.4983 155.56C91.4965 158.06 90.2762 160.548 81 172.06C79.098 173.582 77.7613 173.849 74.9983 173.56C73.3872 177.861 72.6372 180.217 74.9983 183.06C77.8246 182.997 79.4775 183.211 82.9983 185.56C91.9936 185.018 95.3654 183.296 99.9983 179.06C108.577 171.372 110.215 166.985 108.998 159.06C106.052 152.654 103.13 150.958 95.4983 151.56Z" fill="#FC766C" fill-opacity="0.53" stroke="#F48677"/>
        <path d="M63.5 156.06H50C45.7586 157.014 44.9309 158.578 44.5 162.06V173.56C46.2081 181.107 47.2875 184.933 50.5 187.56C55.2521 187.784 57.5551 187.616 59.5 185.56C64.7387 180.171 67.8196 177.221 74.5 172.56C77.8283 172.287 79.4695 172.015 80.5 170.56C85.7989 163.625 90.4639 158.174 90 156.56C89.3589 155.023 88.8454 154.268 87 153.56L73 151.56C68.0179 152.63 66.18 153.746 63.5 156.06Z" fill="#C94C46" stroke="#CB6A5A"/>
        <path d="M54 168.199V171.199C57.2617 172.707 58.0769 172.784 62 171.199C62 171.199 62.5 175.199 63.5 176.199C64.5 177.199 67.5 178.199 67.5 178.199L68.5 176.199L67 175.699C64.7475 174.046 64.77 173.028 65 171.199L67.5 165.199C67.9287 163.016 67.5049 162.715 66 163.199L63.5 168.699L60.5 166.199C56.7006 165.776 55.2824 166.219 54 168.199Z" fill="#2E5154" stroke="#975757"/>
        <path d="M77.5 151.56V58.0599C81.6931 58.258 84.0535 58.3679 84 59.0599L84.5 81.0599H83.5C82.3089 79.3136 81.301 78.8967 79 79.0599V82.0599L84.5 84.5599L85.5 153.06L77.5 151.56Z" fill="#FB776C" stroke="#F8BE99"/>
        <path d="M105 62.0599C97.1874 59.8962 92.8113 60.0874 85 62.0599V70.0599C88.5106 69.2422 90.6356 68.8209 96.5 68.5599C101.777 68.8352 104.076 69.1983 107.5 70.0599C109.819 69.6807 110.113 68.8766 110 67.0599C109.129 64.3512 107.99 63.2763 105 62.0599Z" fill="#D16069" stroke="#EA8078"/>
        <path d="M69.5 52.5599V59.0599C72.838 61.074 74.123 60.7894 75 57.0599C78.9745 56.9127 81.1673 56.8743 84.5 57.5599L88 60.0599L90.5 59.5599C86.4464 55.7772 84.2993 55.0416 80.5 54.0599H75C75.0933 52.6782 75.4541 51.8218 77 50.0599C77.7095 48.5134 76.8417 48.1309 75 47.5599L69.5 52.5599Z" fill="#F3931B"/>
        <path d="M91 72.0599C90.8709 70.7021 91.5139 70.1899 93.5 69.5599H98V72.5599H94.5L90.5 76.5599H92.5C94.029 76.6006 94.0161 77.4877 93.5 79.5599C91.7686 80.4116 90.4004 80.5874 87.5 80.5599C85.8423 79.4836 85.4902 78.2697 86 75.0599H90L92.5 72.5599L91 72.0599Z" fill="#F3931B"/>
        <path d="M69.5 52.5599V59.0599C72.838 61.074 74.123 60.7894 75 57.0599C78.9745 56.9127 81.1673 56.8743 84.5 57.5599L88 60.0599L90.5 59.5599C86.4464 55.7772 84.2993 55.0416 80.5 54.0599H75C75.0933 52.6782 75.4541 51.8218 77 50.0599C77.7095 48.5134 76.8417 48.1309 75 47.5599L69.5 52.5599Z" stroke="#ECBB70"/>
        <path d="M91 72.0599C90.8709 70.7021 91.5139 70.1899 93.5 69.5599H98V72.5599H94.5L90.5 76.5599H92.5C94.029 76.6006 94.0161 77.4877 93.5 79.5599C91.7686 80.4116 90.4004 80.5874 87.5 80.5599C85.8423 79.4836 85.4902 78.2697 86 75.0599H90L92.5 72.5599L91 72.0599Z" stroke="#ECBB70"/>
        <path d="M90.6409 139.811L106.43 146.536C106.43 146.536 107.892 147.12 107.892 148.582V164.663H109.061L107.892 166.856L108.184 189.656C108.184 193.444 104.675 193.444 104.675 193.444H92.3952L83.039 197.995H81.2847V196.825L82.7466 196.533L81.2847 196.241V195.364H84.7933L88.8866 193.444L86.2552 193.317L82.4542 194.779H81.2847V193.999L82.7466 193.444H81.2847V192.732H83.6237L85.378 192.147L84.5009 191.563L83.039 191.855L81.2847 192.147V191.563L82.7466 190.978H81.2847V190.101H83.6237L85.9628 190.978H89.179L85.0856 188.931H83.039L81.2847 189.223V188.054H83.039L81.2847 187.469V186.3C81.2847 186.3 82.4542 186.3 83.039 186.592C83.6237 186.884 92.3952 190.978 92.3952 190.978H104.675C105.845 190.978 105.845 189.656 105.845 189.656V167.587L104.091 164.663H105.552V148.582L89.7638 141.857L90.6409 139.811Z" fill="#F90304"/>
        <path d="M105.845 167.587L106.722 169.049L107.892 166.856M105.845 167.587L104.091 164.663H105.552V148.582L89.7638 141.857L90.6409 139.811L106.43 146.536C106.43 146.536 107.892 147.12 107.892 148.582V164.663H109.061L107.892 166.856M105.845 167.587V189.656C105.845 189.656 105.845 190.978 104.675 190.978H92.3952C92.3952 190.978 83.6237 186.884 83.039 186.592C82.4542 186.3 81.2847 186.3 81.2847 186.3V187.469L83.039 188.054H81.2847V189.223L83.039 188.931H85.0856L89.179 190.978H85.9628L83.6237 190.101H81.2847V190.978H82.7466L81.2847 191.563V192.147L83.039 191.855L84.5009 191.563L85.378 192.147L83.6237 192.732H81.2847V193.444H82.7466L81.2847 193.999V194.779H82.4542L86.2552 193.317L88.8866 193.444L84.7933 195.364H81.2847V196.241L82.7466 196.533L81.2847 196.825V197.995H83.039L92.3952 193.444H104.675C104.675 193.444 108.184 193.444 108.184 189.656L107.892 166.856" stroke="black" stroke-width="0.584766"/>
        <path d="M72 133L54.0933 126.069C54.0933 126.069 50.8771 124.315 50.8771 127.823V147.998V165.833L52.0467 164.685L50 169.048H50.8771V190.867C50.8771 190.867 50.8771 193.321 53.5086 193.194L57.3096 193.321H69.5896L78.9459 197.849H80.7002V196.685L79.2383 196.394L80.7002 196.103V195.231H77.1916L73.0982 193.321L75.7297 193.194L79.5307 194.649H80.7002V193.873L79.2383 193.321H80.7002V192.612H78.3611L76.6068 192.031L77.484 191.449L78.9459 191.74L80.7002 192.031V191.449L79.2383 190.867H80.7002V189.994H78.3611L76.0221 190.867H72.8059L76.8992 188.831H78.9459L80.7002 189.122V187.958H78.9459L80.7002 187.376V186.212C80.7002 186.212 79.5307 186.212 78.9459 186.503C78.3611 186.794 69.5896 190.867 69.5896 190.867H57.3096H53.5086V169.048H54.6781L52.0467 164.685L53.5086 165.833L52.9238 127.823L71.5 134.5L72 133Z" fill="#0B0C82"/>
        <path d="M50.8771 147.998V165.833FL52.0467 164.685M50.8771 147.998C50.8771 146.975 50.8771 131.332 50.8771 127.823M50.8771 147.998V127.823M52.0467 164.685L53.5086 165.833L52.9238 127.823L71.5 134.5L72 133L54.0933 126.069C54.0933 126.069 50.8771 124.315 50.8771 127.823M52.0467 164.685L54.6781 169.048H53.5086M52.0467 164.685L50 169.048H50.8771M53.5086 169.048V190.867H57.3096H69.5896C69.5896 190.867 78.3611 186.794 78.9459 186.503C79.5307 186.212 80.7002 186.212 80.7002 186.212V187.376L78.9459 187.958H80.7002V189.122L78.9459 188.831H76.8992L72.8059 190.867H76.0221L78.3611 189.994H80.7002V190.867H79.2383L80.7002 191.449V192.031L78.9459 191.74L77.484 191.449L76.6068 192.031L78.3611 192.612H80.7002V193.321H79.2383L80.7002 193.873V194.649H79.5307L75.7297 193.194L73.0982 193.321L77.1916 195.231H80.7002V196.103L79.2383 196.394L80.7002 196.685V197.849H78.9459L69.5896 193.321H57.3096L53.5086 193.194C50.8771 193.321 50.8771 190.867 50.8771 190.867V169.048M53.5086 169.048H50.8771" stroke="black" stroke-width="0.584766"/>
        <path d="M84.2088 126.069C80.9926 125.484 77.7968 126.192 75.4373 127.823C73.0054 129.939 72.1892 130.798 71.9287 131.624C71.0178 136.302 71.1826 137.974 72.5135 139.518L76.6068 143.612C79.1551 146.122 82.7469 147.413 84.7936 147.12C86.8402 146.828 89.7574 142.454 90.3488 139.811C91.5042 133.286 87.425 126.654 84.2088 126.069Z" fill="url(#paint0_linear_62_13)" stroke="black" stroke-width="0.584766"/>
        <path d="M78.9453 130.455C78.308 129.296 78.0682 128.408 76.6063 128.408C75.1443 128.408 73.5042 131.25 73.0977 133.086C73.1875 135.656 73.2231 137.123 74.852 136.887C77.4683 136.552 78.6078 136.159 80.1148 135.133C80.2158 133.925 79.2377 133.963 79.2377 132.794C79.2377 131.624 79.2767 131.152 78.9453 130.455Z" fill="#01046E" stroke="black" stroke-width="0.584766"/>
        <path d="M83.3313 135.425C82.7176 135.808 82.6822 136.082 82.7466 136.595C82.7466 136.595 85.0855 143.612 85.9627 144.196C86.8398 144.781 87.6017 142.536 88.0094 141.273C89.0416 136.227 89.5544 133.573 88.5941 133.963L83.3313 135.425Z" fill="#FA0102" stroke="black" stroke-width="0.584766"/>
        <path d="M74.5603 138.641C73.9753 139.226 75.6981 140.286 76.0223 140.688C76.0223 140.688 81.6603 145.193 82.7139 145.229C83.7675 145.266 83.2353 142.955 82.9184 141.666C81.1447 136.831 80.4077 136.887 78.6534 136.887C76.8992 136.887 75.1454 138.057 74.5603 138.641Z" fill="#01046E" stroke="black" stroke-width="0.584766"/>
        <path d="M88.3015 132.794C87.5153 133.746 81.8691 134.548 81.8691 134.548L79.2377 129.285C78.5815 127.93 79.151 127.399 80.992 126.654C83.0025 126.618 84.0576 127.009 85.6701 128.408C88.1598 130.772 89.0878 131.842 88.3015 132.794Z" fill="#FA0102" stroke="black" stroke-width="0.584766"/>
        <path d="M82.6209 92.0046H79.5508C77.7083 92.0046 78.9589 100.845 77.7093 99.9867C74.6298 95.9588 73.7095 95.4935 72.7968 96.3027C61.7098 105.065 60.5163 121.477 61.1307 125.161C61.7451 128.845 63.9002 131.855 66.0427 131.301C70.5605 130.243 72.5615 128.917 75.2528 125.161C79.4337 118.299 78.9554 114.11 78.9368 106.741C80.6926 103.453 81.7402 102.888 83.8489 106.741C84.6521 118.103 85.234 123.05 86.9189 125.161C89.601 129.239 96.129 131.915 97.971 131.301C99.813 130.687 102.165 120.812 101.655 117.793C94.7622 98.6621 92.1379 94.8622 89.3749 96.3027C88.2855 97.1297 87.7148 97.6379 86.9189 98.7587C85.6268 100.637 84.9257 101.11 83.8489 98.7586C83.8492 94.7835 84.0952 91.8684 82.6209 92.0046Z" fill="#82BEF3" stroke="#000B20" stroke-width="1.22801"/>
        <path d="M81.869 98H83.6233L93.272 102.386H106.137C107.319 102.44 107.917 102.548 107.891 104.14V110.572H109.353L106.722 115.251L107.891 114.373V119.929C107.87 120.473 107.665 120.786 106.137 121.391L88.8862 129.577L87.4243 128.408L105.552 119.636V114.373L106.722 115.251L104.675 110.572H105.844V104.14H93.272L83.6233 108.818H81.869V108.233L83.0386 107.941V107.356H81.5767V106.479H83.9157L85.3776 106.771L89.7634 104.432H86.5472L83.331 105.894H81.5767V105.017H83.331L83.9157 104.432H81.5767V103.555H85.9624L84.7929 102.971H81.5767V102.093H83.0386L81.5767 101.216V100.339L84.5005 100.924L87.1319 102.093H89.471L86.2548 100.339L81.5767 99.4619L83.0386 99.1695L81.869 98.8771V98Z" fill="#EF2124"/>
        <path d="M80.9923 98H79.238L69.5893 102.386H56.7245C55.542 102.44 54.9446 102.548 54.9702 104.14L55.1164 112.765L54.0931 114.958H54.9702V119.929C54.9911 120.473 55.1967 120.786 56.7245 121.391L73.9751 129.577L75.437 128.408L57.3093 119.636V114.958H58.4788L57.3093 112.765L57.0169 104.14H69.5893L79.238 108.818H80.9923V108.233L79.8228 107.941V107.356H81.2847V106.479H78.9456L77.4837 106.771L73.0979 104.432H76.3142L79.5304 105.894H81.2847V105.017H79.5304L78.9456 104.432H81.2847V103.555H76.8989L78.0685 102.971H81.2847V102.093H79.8228L81.2847 101.216V100.339L78.3608 100.924L75.7294 102.093H73.3903L76.6065 100.339L81.2847 99.4619L79.8228 99.1695L80.9923 98.8771V98Z" fill="#0B0C82"/>
        <circle cx="75" cy="165" r="5" fill="red" stroke="black" stroke-width="1"
          @click="showInfo('body','Foie', 'Décompose l\'alcool, les drogues et les autres toxines présentes dans le sang afin que ces substances puissent être évacuées du corps par les selles ou l\'urine')"
        />
        <circle cx="61" cy="169" r="4" fill="red" stroke="black" stroke-width="1"
          @click="showInfo('body','Vésicule Biliaire', 'La vésicule biliaire est une petite poche située sous le foie. Son rôle consiste à stocker la bile avant qu\'elle se déverse dans l\'intestin, ce qui arrive en particulier au moment de la digestion. Sécrétée par le foie, la bile est un liquide qui facilite la digestion des graisses.')"
        />

        
        <defs>
          <linearGradient id="paint0_linear_62_13" x1="80.9531" y1="125.866" x2="80.9531" y2="147.161" gradientUnits="userSpaceOnUse">
          <stop stop-color="#EC3E40"/>
          <stop offset="1" stop-color="#862324"/>
          </linearGradient>
        </defs>
      </svg>
    </div>
    <transition name="fade">
      <div class="info-container">
        <div class="title-container">
          <h3 v-if="selectedBodyPart">{{ selectedBodyPart.name }}</h3>
        </div>
        <div class="text-container">
          <p v-if="selectedBodyPart">
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
      selectedBodyPart: null    // Stores selected part info for body
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

.fade-enter-active, .fade-leave-active {
  transition: opacity 0.6s ease, transform 0.6s ease;
}
.fade-enter-from, .fade-leave-to {
  opacity: 0;
  transform: translateY(10px);
}

.body-container {
    width: 300px;
    height: 900px;
    margin: 0 auto;

    img {
      width: 100%;
      height: 100%;
    }
  }

circle {
  cursor: pointer;
  position: relative;
  z-index: 5;
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
    width: 100%;
    height: 100%;
    margin: 0 auto;

    .text-container {
      line-height: 1.5rem;
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
        margin: 25px auto;
      }

      .text-container {
        margin: 25px auto;
      }
    }
  }
}
</style>
