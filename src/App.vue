<script>
  import Title from "./components/AppTitle.vue"
  import Jumbotron from "./components/AppHero.vue"


  export default {
    data() {
      return {

      };
    },
    components: {
      Title,
      Jumbotron,
    },

    methods: {}

  };
</script>

<template>
  <div>
    <Title></Title>
    <Jumbotron></Jumbotron>
    <a href="https://vitejs.dev" target="_blank">
      <img src="/images/vite_logo.png" class="logo" alt="Vite logo" />
    </a>
    <a href="https://vuejs.org/" target="_blank">
      <img src="./assets/vue.svg" class="logo vue" alt="Vue logo" />
    </a>
  </div>
</template>

<style scoped>
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
  transition: filter 300ms;
}
.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}
.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}
</style>
