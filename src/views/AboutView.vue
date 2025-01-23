<template>
  <main>
    <div class="title-container">
      <h1>Qui suis-je ?</h1>
    </div>
    <div class="text">
      <p>Je m'appelle Kevin et je suis actuellement en attente de formation <span class="red-text">C</span>abin <span class="red-text">C</span>rew <span class="red-text">A</span>ttestation pour devenir steward. J'ai une certification de développeur web et web mobile, et
        je vais regrouper ici la majorité des informations requises pour débuter la formation.
      </p>
    </div>
    <div class="text">
      <p>Ces informations regroupent les formules de conversion, mais aussi un convertisseur instantané, bien qu'il soit nécessaire de faire des estimations
        de calcul à la main.
      </p>
    </div>
  </main>
</template>
<style scoped lang="scss">

.red-text {
  color: red;
}

.text {
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: justify;
  margin: 0 15px;
  line-height: 25px;
  font-family: 'Noto Sans', Courier, monospace;
  letter-spacing: 2px;
}
@media (min-width: 320px) and (max-width: 990px) {
  main {
  display: grid;
  grid-template-columns: repeat(1, 1fr);
  grid-template-rows: repeat(1, 1fr);
  row-gap: 50px;
  letter-spacing: 2px;

}
}

</style>