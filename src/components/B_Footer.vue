<template>
  <section id="b-footer">
    <div class="container">
      <div class="footer-buttons">
        <a class="signup-btn" href="#">SIGN-UP NOW!</a>

        <div class="socials">
          <h2>FOLLOW US</h2>
          <ul>
            <li>
              <a href="#">
                <img src="../assets/img/footer-facebook.png" alt="facebook" />
              </a>
            </li>
            <li>
              <a href="#">
                <img src="../assets/img/footer-twitter.png" alt="twitter" />
              </a>
            </li>
            <li>
              <a href="#">
                <img src="../assets/img/footer-youtube.png" alt="youtube" />
              </a>
            </li>
            <li>
              <a href="#">
                <img src="../assets/img/footer-pinterest.png" alt="pinterest" />
              </a>
            </li>
            <li>
              <a href="#">
                <img src="../assets/img/footer-periscope.png" alt="periscope" />
              </a>
            </li>
          </ul>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "B_Footer",
};
</script>

<style lang="scss" scoped>
@import "../assets/scss/vars.scss";

#b-footer {
  background-color: #303030;
  position: relative;
  .footer-buttons {
    display: flex;
    justify-content: space-between;
    padding: 2rem 0;
    .signup-btn {
      color: white;
      padding: 10px 15px;
      border: 2px solid $primary_color;
      &:hover {
        background-color: $primary_color;
      }
    }
    .socials {
      display: flex;
      h2 {
        color: $primary_color;
        padding: 0 20px;
      }
      ul {
        display: flex;
        a {
          margin-left: 15px;
        }
      }
    }
  }
}
</style>