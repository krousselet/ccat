<script setup>
import HeaderDisplay from './components/HeaderDisplay.vue';

</script>

<template>
  <HeaderDisplay>
  </HeaderDisplay>
    <nav>
    <router-link to="/">Home</router-link>
      <router-link to="/about">Details</router-link>
      <router-link to="/convert">Convertir</router-link>
      <router-link to="/technicalterms">Glossaire</router-link>
      <router-link to="/aircraft">Avion</router-link>
      <router-link to="/altitude">Altitude</router-link>
      <router-link to="/body">Corps</router-link>
    </nav>
  <router-view />
</template>

<style lang="scss">

// CUSTOM SCROLLBAR
/* Apply styles to the scrollbar */
::-webkit-scrollbar {
  width: 8px; /* Width of the scrollbar */
}

/* Track (background) */
::-webkit-scrollbar-track {
  background: #f1f1f1; /* Light grey background */
  border-radius: 10px;
}

/* Handle (scrollbar itself) */
::-webkit-scrollbar-thumb {
  background: #002157; /* Red color */
  border-radius: 10px;
  transition: background 0.3s ease;
}

/* Handle on hover */
::-webkit-scrollbar-thumb:hover {
  background: #d62828; /* Darker red on hover */
}


#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;

}
li {
  list-style: none;
}
nav {
  padding: 30px;
  display: flex;
  justify-content: space-around;
  align-items: center;
  width: 100%;
  margin: 0 auto;
  flex-wrap: wrap;
  gap: 10px;

  a {
    font-weight: bold;
    color: black;
    display: flex;
    justify-content: center;
    align-items: center;
    text-decoration: none;

    &.router-link-exact-active {
      color: red;
    }
  }
}

.title-container {
  display: flex;
  justify-content: center;
  align-items: center;
}

/* ANIMATIONS */

.fade-enter-active,
.fade-leave-active {
    transition: opacity 0.5s;
}

.fade-enter-from,
.fade-leave-to {
    opacity: 0;
}

/* GENERAL */

*,
::before,
::after {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

input {
    border: 0;
    border-bottom: 1px solid black;
    width: 25%;
}

button {
    background-color: rgb(0, 33, 87);
    border: none;
    color: white;
    padding: 5px;
    border-radius: 7px;
}

.title-container {
    display: flex;
    justify-content: center;
    align-items: center;
}

section {
    margin: 25px auto;
}

/* HEADER */
header {
    display: block;
    width: 100%;
    height: 80px;
    border-radius: 0 0 7px 7px;
}

.three-colors-container {
    display: flex;
    justify-content: center;
    align-items: center;
    height: inherit;
    border-radius: 0 0 7px 7px;
}

.blue,
.white,
.red {
    background: rgb(0, 33, 87);
    width: 33%;
    height: inherit;
}

.blue {
    border-radius: 0 0 0 7px;
}

.white {
    background: white;
}

.red {
    background: rgb(247, 29, 37);
    border-radius: 0 0 7px 0;
}

@keyframes appear {
  100% {
    opacity: 1;
  }
}
</style>
