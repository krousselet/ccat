<template>
    <div class="title-container">
      <h1>{{ title }}</h1>
    </div>
  </template>
  
  <script>
  export default {
    name: "TechnicalTerms",
    props: {
      title: String,
    },
  };
  </script>
  
  <!-- Add "scoped" attribute to limit CSS to this component only -->
  <style scoped lang="scss">

  </style>
  