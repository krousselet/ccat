<template>
    <table>
        <tr>
            <th>Maladies</th>
            <th>Mode de Contamination</th>
            <th>Agents</th>
            <th>Prévention</th>
        </tr>

        <tr class="category"><td colspan="4">PARASITAIRES</td></tr>
        <tr><td>Amibiase</td><td>Voie digestive</td><td>Amibe pathogène</td><td>Hygiène alimentaire</td></tr>
        <tr><td>Bilharziose</td><td>Voie transcutanée</td><td>Bilharzie</td><td>Éviter les baignades en eau douce</td></tr>
        <tr><td>Paludisme</td><td>Piqûre d'Anophèle</td><td>Plasmodium</td><td>Chimioprophylaxie, protection contre les piqûres d’insectes</td></tr>

        <tr class="category"><td colspan="4">VIRALES</td></tr>
        <tr><td>Dengue</td><td>Piqûre d'Aedes</td><td>Arbovirus de la dengue</td><td>Protection contre piqûres d’insectes</td></tr>
        <tr><td>Fièvre Jaune</td><td>Piqûre d'Aedes</td><td>Virus amaril</td><td>Vaccin antiamaril</td></tr>
        <tr><td>Coronavirus</td><td>Voies aériennes</td><td>Coronavirus</td><td>Gants et masques</td></tr>
        <tr><td>Hépatites virales</td><td>A : voie digestive, B/C : sécrétions corporelles</td><td>VHA, VHB, VHC</td><td>Vaccins anti-VHA et VHB</td></tr>
        <tr><td>Rage</td><td>Voie cutanée</td><td>Lyssavirus</td><td>Vaccin antirabique, désinfection</td></tr>
        <tr><td>SRAS</td><td>Voie aérienne</td><td>Coronavirus du SRAS</td><td>Gants et masques</td></tr>
        <tr><td>Ebola</td><td>Voie digestive, sécrétions corporelles</td><td>Virus Ebola</td><td>Hygiène alimentaire, port de gants</td></tr>
        <tr><td>VIH</td><td>Secrétions corporelles</td><td>Virus de l’immunodéficience humaine</td><td>Protection rapports sexuels, matériel stérile, gants présence de sang</td></tr>

        <tr class="category"><td colspan="4">BACTÉRIENNES</td></tr>
        <tr><td>Choléra</td><td>Voie digestive</td><td>Vibrion cholérique</td><td>Vaccin anticholérique</td></tr>
        <tr><td>Salmonellose</td><td>Voie digestive</td><td>Salmonella</td><td>Hygiène alimentaire</td></tr>
        <tr><td>Maladie de Lyme</td><td>Piqûre de tique</td><td>Borrelia burgdorferi</td><td>Vêtements couvrants, insecticides</td></tr>
        <tr><td>Tétanos</td><td>Voie cutanée</td><td>Bacille du tétanos</td><td>Vaccin antitétanique</td></tr>
        <tr><td>Tuberculose</td><td>Voie aérienne</td><td>Bacille de Koch</td><td>BCG</td></tr>
    </table>
</template>
  
  <script>
  export default {
    name: "HurtComponent",
  };
  </script>
  
  <!-- Add "scoped" attribute to limit CSS to this component only -->
  <style scoped lang="scss">
  table {
            width: 100%;
            border-collapse: collapse;
        }
        th, td {
            outline: 1px solid black;
            padding: 8px;
            text-align: center;
            overflow-x: hidden;
        }
        th {
            background-color: #c2c2f0;
        }
        .category {
            background-color: #e6e6e6;
            font-weight: bold;
            text-align: center;
        }

        @media (min-width:320px) and (max-width:991px) {
            th, td {
            outline: 1px solid black;
            display: flex;
            padding: 8px;
            justify-content: center;
            align-items: center;
            text-align: center;
            }
            tr {
                display: grid;
                grid-template-columns: repeat(4, 1fr);
                grid-template-rows: 1fr;
            }


            .category {
                display: grid;
                grid-template-columns: 1fr;
            }

            td {
                display: grid;
                grid-template-columns: repeat(4, 1fr);
                grid-template-rows: 1fr;
            }
        }
  </style>
  