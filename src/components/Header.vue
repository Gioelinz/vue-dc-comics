<template>
  <header>
    <div class="container">
      <div class="nav-container">
        <figure>
          <img src="../assets/img/dc-logo.png" alt="DC Logo" />
        </figure>
        <nav>
          <ul>
            <li><a href="#">CHARACTERS</a></li>
            <li><a href="#" class="active">COMICS</a></li>
            <li><a href="#">MOVIES</a></li>
            <li><a href="#">TV</a></li>
            <li><a href="#">GAMES</a></li>
            <li><a href="#">COLLECTIBLES</a></li>
            <li><a href="#">VIDEOS</a></li>
            <li><a href="#">FANS</a></li>
            <li><a href="#">NEWS</a></li>
            <li><a href="#">SHOP</a></li>
          </ul>
        </nav>
      </div>
    </div>
  </header>
</template>

<script>
export default {
  name: "Header",
};
</script>

<style scoped lang="scss">
@import "../assets/scss/vars.scss";

.nav-container {
  display: flex;
  align-items: center;
  justify-content: space-between;
  padding: 13px 0;
}

ul {
  display: flex;
  padding: 2rem 0;
}

ul li {
  list-style-type: none;
  padding: 1rem;
}
ul li a {
  text-decoration: none;
  color: rgb(88, 88, 88);
  font-size: 0.9rem;
  font-weight: bold;
  padding: 100% 0;
}

ul li a.active {
  color: $primary_color;
  border-bottom: 5px solid $primary_color;
}
</style>

