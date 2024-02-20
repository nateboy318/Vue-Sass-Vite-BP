<script setup>
import HelloWorld from "./components/HelloWorld.vue";
import Btn from "./components/Btn.vue";
</script>

<template>
  <div class="container">
    <a href="https://vitejs.dev" target="_blank">
      <img src="./assets/vite.svg" class="logo vite" alt="Vite logo" />
      <span> +</span>
    </a>
    <a href="https://vuejs.org/" target="_blank">
      <img src="./assets/vue.svg" class="logo vue" alt="Vue logo" />
      <span> +</span>
    </a>
    <a href="https://https://sass-lang.com//" target="_blank">
      <img src="./assets/sass.svg" class="logo sass" alt="Sass logo" />
    </a>
  </div>
  <HelloWorld />
  <Btn />
</template>

<style scoped>
.container {
  display: flex;
  justify-content: center;
  flex-wrap: wrap;
}
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
  transition: filter 300ms;
  @media screen and (max-width: 590px) {
    height: 3em;
  }
}
.logo.vite:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}
.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}

.logo.sass:hover {
  filter: drop-shadow(0 0 2em #e54bafaa);
}
a {
  display: flex;
  align-items: center;
  text-decoration: none;
}
span {
  color: white;
  font-size: 75px;
  font-weight: 600;
  @media screen and (max-width: 590px) {
    font-size: 37px;
  }
}
</style>
