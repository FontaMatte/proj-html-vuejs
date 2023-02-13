<script>

export default {

  name: 'AppHeader',
  data() {
    return {

    };
  },
  components: {

  }
}
</script>

<template>
  <header>
    <!-- HEADER TOP -->
    <div class="header-top">
      <div class="main-logo">
        LOGO + TITLE
      </div>
      <div class="nav-bar">
        <ul>
          <li><a href="#"></a>Home</li>
          <li><a href="#"></a>Home</li>
          <li><a href="#"></a>Home</li>
          <li><a href="#"></a>Home</li>
          <li><a href="#"></a>Home</li>
          <li><a href="#"></a>Home</li>
        </ul>
        <button>VIEW COURSES</button>
      </div>
    </div>

    <!-- HEADER BOTTOM -->
    <div class="header-bottom">
      <div class="aside-menu">
        <img src="" alt="">
        <img src="" alt="">
        <img src="" alt="">
        ASIDE MENU
      </div>
      <div class="container">
        <div class="header-bottom-content">
          <h1>
            Key to your succes
          </h1>
          <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. 
            Voluptatem sequi nobis quod quis nostrum dicta.
          </p>
          <button>Search courses</button>
          <button>Apply for university</button>
        </div>
      </div>
    </div>
  </header>
</template>

<style lang="scss" scoped>
@import "../styles/partials/appHeader.scss";
</style>