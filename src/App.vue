<template>
  <div id="app">
    <the-navbar></the-navbar>
    <the-profile></the-profile>
    <the-footer></the-footer>
  </div>
</template>

<script>
import TheNavbar from './components/TheNavbar.vue'
import TheProfile from './components/TheProfile.vue'
import TheFooter from './components/TheFooter.vue'

export default {
  components: {
    TheNavbar,
    TheProfile,
    TheFooter,
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
}
</style>
