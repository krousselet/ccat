<template>
  <main>
    <div class="container">
      <div class="title-container">
        <h1>Qui suis-je ?</h1>
      </div>
      <div class="text text-zero">
        <p>Je suis actuellement en attente de formation <span class="red-text">Personnels Navigants Commerciaux | Cabin Crew Attestation</span> pour devenir steward. J'ai une certification de développeur web et web mobile, et
          je vais regrouper ici la majorité des informations requises pour débuter la formation.
        </p>
      </div>
    </div>
    <div class="container">
      <div class="text">
        <p>Ces informations regroupent les formules de conversion, mais aussi un convertisseur instantané, bien qu'il soit nécessaire de faire des estimations
          de calcul à la main. Vous trouverez aussi un swiper avec un certain nombre d'abbréviations et leur signification. Enfin, vous trouverez des informations sur les différents avions dans lesquels vous aurez le plaisir de servir.
        </p>
      </div>
      <div class="title-container">
          <h2>Pourquoi ?</h2>
      </div>
    </div>
  </main>
</template>
<style scoped lang="scss">

.red-text {
  color: red;
}

@media (min-width: 320px) and (max-width: 990px) {
  .title-container {
      width: 100%;
      margin: 50px auto;
      font-size: 4vw;
    }

  .text {
  display: flex;
  width: 95%;
  justify-content: center;
  align-items: center;
  text-align: justify;
  margin: 0 auto;
  line-height: 33px;
  font-family: 'Noto Sans', Courier, monospace;
  }
}



@media (min-width: 992px) and (max-width: 2048px) {
  .container {
    display: grid;
    grid-template-columns: 1fr 1fr;
    grid-template-rows: 1fr;
    width: 100%;
    margin: 0 auto;
    margin-top: 10vh;

    .title-container {
      width: 50%;
      margin: 0 auto;
      font-size: 2vw;
    }

    .text {
      margin: 0 auto;
      margin-right: 100px;
      width: 100%;
      font-size: 1.5vw;
      line-height: 10vh;
    }
  }
}

@media (min-width: 2049px) {
  .container {
    display: grid;
    grid-template-columns: repeat(2, 1fr);
    grid-template-rows: 1fr; 

    .title-container {
      font-size: 30vw;
    }

    .text-zero {
      margin-top: 50px;
      line-height: 10px;
    }
  }

}

</style>