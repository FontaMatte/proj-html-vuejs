<script>
import AppHeader from './components/AppHeader.vue';
import AppMain from './components/AppMain.vue';
import AppFooter from './components/AppFooter.vue';

export default {
  name: 'App',
  data() {
    return {
      navBarLinks: [
        {
        link: 'Home',
        isSelected: true,
        caretDown: true
        },
        {
        link: 'Courses',
        isSelected: false,
        caretDown: true
        },
        {
        link: 'About Us',
        isSelected: false,
        caretDown: false
        },
        {
        link: 'News',
        isSelected: false,
        caretDown: true
        },
        {
        link: 'Pages',
        isSelected: false,
        caretDown: true
        },
        {
        link: 'Contact',
        isSelected: false,
        caretDown: false
        },
        {
        link: 'Purchase',
        isSelected: false,
        caretDown: false
        }          
      ],
      getEduPrimeLinks: [
        'Request a website',
        'Browse Themes',
        'Payment options',
        'Support System',
        'Checkout',
        'Purchase Theme',
      ],
      networkingLinks: [
        'Purchase Theme',
        'Our Benefits',
        'Our Team',
        'Our Services',
        'Other products',
        'My account',
      ],
      searchCategories: [
        'economy',
        'design',
        'coaching',
        'business',
        'medicine',
        'law',
        'fitness'
      ]

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
  
  <AppFooter 
  :GetEduPrimeLinks="getEduPrimeLinks"
  :NetworkingLinks="networkingLinks"
  :SearchCategories="searchCategories"
  />

</template>

<style lang="scss">
@import "./styles/global.scss";
</style>
