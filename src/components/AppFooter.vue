<script>

export default {

  name: 'AppFooter',
  data() {
    return {

    };
  },
  components: {

  }
}
</script>

<template>
  <footer>
    <div class="button-container">
      <button class="call-to-action-button">Purchase Theme</button>
      <button class="call-to-action-button">Related Themes</button>
    </div>
    <div class="container">
      <div class="company-info">
        <div class="company-name">
          <img src="" alt="">
          <h2>EduPrime</h2>
        </div>
        <p>
          EduPrime is the most versatile WordPress theme for educational purpose,showcasing universities,
          courses,secondaryschools etc.
        </p>
        <div class="social">
          <img src="" alt="FB">
          <img src="" alt="TW">
          <img src="" alt="IG">
        </div>
      </div>
      <div class="get-edu-prime">
        <h3>
          Get EduPrime
        </h3>
        <ul>
          <li>Request a website</li>
          <li>Request a website</li>
          <li>Request a website</li>
          <li>Request a website</li>
          <li>Request a website</li>
          <li>Request a website</li>
        </ul>
      </div>
      <div class="networking">
        <h3>
          Networking
        </h3>
        <ul>
          <li>Request a website</li>
          <li>Request a website</li>
          <li>Request a website</li>
          <li>Request a website</li>
          <li>Request a website</li>
          <li>Request a website</li>
        </ul>
      </div>
      <div class="search-categories">
        <div class="input">
          <input type="text" placeholder="Search...">
          <button>LENTE</button>
        </div>
        <span>
          search categories
        </span>
        <div class="categories">
          <span>ECONOMY</span>
          <span>DESIGN</span>
          <span>COACHING</span>
          <span>BUSINESS</span>
          <span>MEDICINE</span>
        </div>
        <span>
          ModelTheme. All rughts reserved.
        </span>
      </div>
    </div>
    <button class="to-the-top-button">
      <a href="#">TO THE TOP</a>
    </button>
  </footer>
</template>

<style lang="scss" scoped>
@import "../styles/partials/appFooter.scss";
</style>