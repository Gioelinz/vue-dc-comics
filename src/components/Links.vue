<template>
  <section id="links">
    <div class="container d-flex">
      <div class="item-link">
        <a href="#">
          <img
            src="../assets/img/buy-comics-digital-comics.png"
            alt="Digital comics"
          />
          DIGITAL COMICS
        </a>
      </div>
      <div class="item-link">
        <a href="#">
          <img
            src="../assets/img/buy-comics-merchandise.png"
            alt="Digital comics"
          />
          DC MERCHANDISE
        </a>
      </div>
      <div class="item-link">
        <a href="#">
          <img
            src="../assets/img/buy-comics-subscriptions.png"
            alt="Digital comics"
          />
          SUBSCRIPTION
        </a>
      </div>
      <div class="item-link">
        <a href="#">
          <img
            src="../assets/img/buy-comics-shop-locator.png"
            alt="Digital comics"
          />
          COMIC SHOP LOCATOR
        </a>
      </div>
      <div class="item-link">
        <a href="#">
          <img src="../assets/img/buy-dc-power-visa.svg" alt="Digital comics" />
          DC POWER VISA
        </a>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "Links",
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