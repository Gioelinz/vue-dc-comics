<template>
  <header>
    <div class="container">
      <div class="nav-container">
        <figure>
          <img src="../assets/img/dc-logo.png" alt="DC Logo" />
        </figure>
        <nav>
          <ul>
            <li v-for="navItem in navItems" :key="navItem.text">
              <a href="#" :class="{ active: navItem.active }">{{
                navItem.text
              }}</a>
            </li>
          </ul>
        </nav>
      </div>
    </div>
  </header>
</template>

<script>
export default {
  name: "Header",
  data() {
    return {
      navItems: [
        { text: "CHARACTERS", active: false },
        { text: "COMICS", active: true },
        { text: "MOVIES", active: false },
        { text: "TV", active: false },
        { text: "GAMES", active: false },
        { text: "COLLECTIBLES", active: false },
        { text: "VIDEOS", active: false },
        { text: "FANS", active: false },
        { text: "NEWS", active: false },
        { text: "SHOP", active: false },
      ],
    };
  },
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
  padding: 1rem;
}
ul li a {
  color: rgb(88, 88, 88);
  font-size: 0.9rem;
  font-weight: bold;
  padding: 3.55rem 0;
}

ul li a.active {
  color: $primary_color;
  border-bottom: 5px solid $primary_color;
}
</style>

