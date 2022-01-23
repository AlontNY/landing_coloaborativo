<template>
  <div id="app">
    <HeaderVue style="min-height:38vh;"></HeaderVue>
    <FooterVue></FooterVue>
  </div>
</template>

<script>

import HeaderVue from './components/header.vue'
import FooterVue from './components/footer.vue'

export default {
  name: 'App',
  components: {
    HeaderVue,
    FooterVue
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
  margin-top: 60px;
}
</style>
