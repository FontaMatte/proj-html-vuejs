<script>

export default {

  name: 'AppFooter',
  data() {
    return {

    };
  },
  props: {
    GetEduPrimeLinks : Array,
    NetworkingLinks : Array,
    SearchCategories : Array,
  }
}
</script>

<template>
  <footer>

    <div class="button-container">
      <button class="call-to-action-button mb-2">
        <img src="../assets/svg/svg-3.svg" alt="">
        Purchase Theme</button>
      <button class="call-to-action-button">
        <img src="../assets/svg/svg-2.svg" alt="">
        Related Themes</button>
    </div>

    <div class="my-container">
      <!-- COMPANY INFO -->
      <div class="company-info">
        <div class="company-logo mb-4">
          <img src="../assets/img/theme_eduprime_logo.png" alt="">
        </div>
        <p class="mb-4">
          EduPrime is the most versatile WordPress theme for educational purpose,showcasing universities,
          courses,secondaryschools etc.
        </p>
        <div class="social">
          <a href=""><i class="fa-brands fa-facebook me-2"></i></a>
          <a href=""><i class="fa-brands fa-twitter me-2"></i></a>
          <a href=""><i class="fa-brands fa-instagram"></i></a>
        </div>
      </div>

      <!-- GET EDU PRIME -->
      <div class="get-edu-prime">
        <h3 class="fs-6">
          Get EduPrime
        </h3>
        <ul>
          <li v-for="link in GetEduPrimeLinks">
            <a href="#">
              {{ link }}
            </a>
          </li>
        </ul>
      </div>
      
      <!-- NETWORKING -->
      <div class="networking">
        <h3 class="fs-6">
          Networking
        </h3>
        <ul>
          <li v-for="link in NetworkingLinks">
            <a href="#">
              {{ link }}
            </a>
          </li>
        </ul>
      </div>

      <!-- SEARCH CATEGORIES -->
      <div class="search-categories">
        <div class="email-input">
          <input type="text" placeholder="Search...">
          <button>
            <i class="fa-solid fa-magnifying-glass"></i>
          </button>
        </div>
        <h6 class="mt-4 mb-3">
          search categories
        </h6>
        <div class="categories mb-3">
          <div v-for="link in SearchCategories">
            <a href="">
              {{ link }}
            </a>
          </div>
        </div>
        <span>
          ModelTheme. All rughts reserved.
        </span>
      </div>
    </div>
    <button class="to-the-top-button">
      <a href="#">
        <img src="../assets/img/back-to-top-arrow.svg" alt="">
      </a>
    </button>
  </footer>
</template>

<style lang="scss" scoped>
@import "../styles/partials/appFooter.scss";
</style>