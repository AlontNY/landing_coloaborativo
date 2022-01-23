<template>
  <div id="app">
    <HeaderVue style="min-height:38vh;"></HeaderVue>
        <img alt="Vue logo" src="./assets/logo.png">
        <HelloWorld msg="Welcome to Your Vue.js App"/>
    <FooterVue></FooterVue>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import HeaderVue from './components/header.vue'
import FooterVue from './components/footer.vue'

export default {
  name: 'App',
  components: {
    HelloWorld,
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
