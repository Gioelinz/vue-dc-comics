<template>
  <div id="app">
    <Header />
  </div>
</template>

<script>
import Header from "./components/Header.vue";

export default {
  name: "App",
  components: {
    Header,
  },
};
</script>

<style lang="scss">
/* Generics */

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: "Rubik", sans-serif;
  font-weight: 500;
}

.container {
  max-width: 1400px;
  margin: 0 auto;
}

img {
  max-width: 100%;
  height: auto;
}
</style>
