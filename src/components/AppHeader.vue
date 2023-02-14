<script>
// import { useAttrs } from 'vue';

export default {

  name: 'AppHeader',
  data() {
    return {
      isSelected: true,
    };
  },
  props: {
    navBarLinks: Array
  }
}
</script>

<template>
  <header>
    <div class="layer"></div>
    <!-- HEADER TOP -->
    <div class="header-top">
      <div class="main-logo">
        <img src="../assets/img/theme_eduprime_logo.png" alt="MainLogo">
      </div>
      <div class="nav-bar">
        <ul>
          <li v-for="link in navBarLinks">
            <a href="#" :class="{ selected: isSelected }">
              {{ link }}
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
      <div class="my-container">
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
  </header>
</template>

<style lang="scss" scoped>
@import "../styles/partials/appHeader.scss";
</style>