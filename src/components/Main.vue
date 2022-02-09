<template>
  <main>
    <div class="jumbo-img">
      <div class="container">
        <h2>CURRENT SERIES</h2>
      </div>
    </div>
    <div class="container"></div>
  </main>
</template>

<script>
export default {
  name: "Main",
};
</script>

<style lang="scss" scoped>
@import "../assets/scss/vars.scss";
main {
  background-color: #1c1c1c;
  color: white;
  .jumbo-img {
    background-image: url(../assets/img/jumbotron.jpg);
    background-repeat: no-repeat;
    background-size: cover;
    min-height: 550px;
    position: relative;
    h2 {
      padding: 10px 15px;
      background-color: $primary_color;
      display: inline-block;
      box-shadow: 0px 1px 10px 1px #000000;
      position: absolute;
      bottom: -25px;
    }
  }
}
</style>