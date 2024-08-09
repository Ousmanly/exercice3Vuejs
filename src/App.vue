<template>
  <section>
    <AppNavbar/> 
    <AppJumbotronn/>
    <AppCTA/>
    <AppCards/>
    <AppFooter/>
  </section>
 
</template>

<script>
import AppNavbar from './components/AppNavbar.vue';
import AppJumbotronn from './components/AppJumbotronn.vue';
import AppCTA from './components/AppCTA.vue';
import AppCards from './components/AppCards.vue';
import AppFooter from './components/AppFooter.vue';

export default {
  name: 'App',
  components: {
    AppNavbar,
    AppJumbotronn,
    AppCTA,
    AppCards,
    AppFooter
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  /* margin-top: 60px; */
}
</style>
