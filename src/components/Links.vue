<template>
  <section id="links">
    <div class="container d-flex">
      <div class="item-link" v-for="(link, index) in blueLinks" :key="index">
        <a href="#">
          <img :src="require('../assets/img/' + link.src)" />
          {{ link.text }}
        </a>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "Links",
  props: {
    blueLinks: Array,
  },
};
</script>

<style lang="scss" scoped>
@import "../assets/scss/vars.scss";

#links {
  background-color: $primary_color;
  .item-link {
    display: flex;
    align-items: center;
    padding: 3rem 0;
    margin: 0 auto;
    cursor: pointer;
    img {
      max-width: 60px;
      max-height: 60px;
      margin-right: 15px;
    }
    a {
      color: white;
      text-decoration: none;
      display: flex;
      align-items: center;
    }
  }
}
</style>