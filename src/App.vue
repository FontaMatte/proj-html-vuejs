<script>
import AppHeader from './components/AppHeader.vue';
import AppMain from './components/AppMain.vue';
import AppFooter from './components/AppFooter.vue';

export default {
  name: 'App',
  data() {
    return {
      navBarLinks: [
          'Home',
          'Courses',
          'About Us',
          'News',
          'Pages',
          'Contact',
          'Purchase'
      ],

    };
  },
  components: {
    AppHeader,
    AppMain,
    AppFooter
  }
}
</script>

<template>

  <AppHeader :navBarLinks="navBarLinks"/>

  <AppMain/>
  
  <AppFooter/>

</template>

<style lang="scss">
@import "./styles/global.scss";
</style>
