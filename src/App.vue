<template>
  <!-- <img alt="Vue logo" src="./assets/logo.png"> -->
  <!-- <HelloWorld msg="Welcome to Your Vue.js App"/> -->
  <div id="app">
    <!-- <HeaderPage/>
    <AboutPage />
    <ContactPage/> -->
    <HomePage/>
  </div>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
// import HeaderPage from './components/HeaderPage.vue';
// import AboutPage from './components/AboutPage.vue';
// import ContactPage from './components/ContactPage.vue';
import HomePage from './components/HomePage.vue';


export default {
  name: 'App',
  components: {
    // HelloWorld,
    // HeaderPage,
    // AboutPage,
    // ContactPage,
    HomePage
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  /* text-align: center;
  color: #2c3e50;
  margin-top: 60px; */
}
</style>
