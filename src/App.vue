<template>
  <div id="app">
    <Header />
    <Main />
    <Links :blue-links="blueLinks" />
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
  data() {
    return {
      blueLinks: [
        { src: "buy-comics-digital-comics.png", text: "DIGITAL COMICS" },
        { src: "buy-comics-merchandise.png", text: "DC MERCHANDISE" },
        { src: "buy-comics-subscriptions.png", text: "SUBSCRIPTION" },
        { src: "buy-comics-shop-locator.png", text: "COMIC SHOP LOCATOR" },
        { src: "buy-dc-power-visa.svg", text: "DC POWER VISA" },
      ],
    };
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
  pointer-events: none;
  user-select: none;
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
