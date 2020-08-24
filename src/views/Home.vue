<template>
  <div id="app">
    <Skills />
  </div>
</template>

<script>
import Skills from "../components/Skills.vue";

export default {
  name: "App",
  components: {
    Skills,
  },
};
</script>

<style scoped>
@import url("https://fonts.googleapis.com/css2?family=Montserrat:wght@400;700&display=swap");

body {
  background-color: #e9ecef;
  font-family: "Montserrat", sans-serif;
  display: grid;
  grid-template-rows: auto;
  justify-items: center;
  align-items: center;
}

body,
html {
  margin: 0;
  height: 100%;
}

#app {
  width: 50%;
}
</style>
