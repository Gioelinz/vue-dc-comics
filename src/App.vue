<template>
  <div id="app">
    <Header />
    <Main />
    <Links />
    <Footer />
    <B_Footer />
  </div>
</template>

<script>
import Header from "./components/Header.vue";
import Main from "./components/Main.vue";
import Links from "./components/Links.vue";
import Footer from "./components/Footer.vue";
import B_Footer from "./components/B_Footer.vue";

export default {
  name: "App",
  components: {
    Header,
    Main,
    Links,
    Footer,
    B_Footer,
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

a {
  text-decoration: none;
}

li {
  list-style-type: none;
}

/* utils */

.d-flex {
  display: flex;
}
</style>
