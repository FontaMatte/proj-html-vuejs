<script>

export default {

  name: 'AppHeader',
  data() {
    return {
      themeSliders:[
        'theme-slider1',
        'theme-slider2',
        'theme-slider3'    
      ],
      currentTheme: 0
    };
  },
  props: {
    navBarLinks: Object
  },
  methods: {

    nextTheme() {

      if (this.currentTheme == this.themeSliders.length - 1) {
        this.currentTheme = 0;
      }
      else {
        this.currentTheme++;
      }

    },
  },
  mounted() {

    setInterval(this.nextTheme,3000);

  }
}
</script>

<template>
  <header>
    <div :class="themeSliders[currentTheme]">
      <div class="layer"></div>
      <!-- HEADER TOP -->
      <div class="header-top">
        <div class="main-logo">
          <img src="../assets/img/theme_eduprime_logo.png" alt="MainLogo">
        </div>
        <div class="nav-bar">
          <ul>
            <li v-for="link in navBarLinks">
              <a href="#" :class="{ selected: link.isSelected }">
                {{ link.link }} 
                <i v-if="link.caretDown" class="fa-solid fa-caret-down ms-2"></i>
              </a>
            </li>
          </ul>
          <button>VIEW COURSES</button>
        </div>
      </div>

      <!-- HEADER BOTTOM -->
      <div class="header-bottom">
        <div class="aside-menu">
          <a href="#"><i class="fa-solid fa-cart-shopping"></i></a>
          <a href="#"><i class="fa-solid fa-book-open"></i></a> 
          <a href="#"><i class="fa-solid fa-life-ring"></i></a> 
        </div>
        <div class="my-container-small">
          <div class="header-bottom-content">
            <h1>
              Key to your succes
            </h1>
            <p class="mb-5">EduPrime is the most bersatile WordPress Theme for educational purposes,
              showcasing universities, courses, secondary schools etc.
            </p>
            <button class="me-4">
              <i class="fa-solid fa-magnifying-glass me-2"></i>
              Search courses
            </button>
            <button>
              <i class="fa-solid fa-user-graduate me-2"></i>
              Apply for university
            </button>
          </div>
        </div>
      </div>
    </div>
  </header>
</template>

<style lang="scss" scoped>
@import "../styles/partials/appHeader.scss";
</style>