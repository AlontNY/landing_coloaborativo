<template>
  <div id="app">
    <HeaderVue style="min-height:38vh;"></HeaderVue>
    <Dominios></Dominios>
    <FooterVue></FooterVue>
  </div>
</template>

<script>

import HeaderVue from './components/header.vue'
import FooterVue from './components/footer.vue'
import Dominios from './components/Dominios.vue'
export default {
  name: 'App',
  components: {
    HeaderVue,
    FooterVue,
    Dominios
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  /*text-align: center;*/
  color: #2c3e50;
  margin-top: 60px;
}
</style>
