<template>
  <div id="app">
    <Header />
    <Main />
    <Links />
  </div>
</template>

<script>
import Header from "./components/Header.vue";
import Main from "./components/Main.vue";
import Links from "./components/Links.vue";

export default {
  name: "App",
  components: {
    Header,
    Main,
    Links,
  },
};
</script>

<style lang="scss">
/* Generics */

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: "Noto Sans", sans-serif;
}

.container {
  max-width: 1400px;
  margin: 0 auto;
}

img {
  max-width: 100%;
  height: auto;
}

/* utils */

.d-flex {
  display: flex;
}
</style>
