<template>
  <div id="app">
    <HeaderVue style="min-height:38vh;"></HeaderVue>
    <Contenido></Contenido>
    <FooterVue></FooterVue>
  </div>
</template>

<script>

import HeaderVue from './components/header.vue'
import FooterVue from './components/footer.vue'
import Contenido from './components/Contenido.vue'
export default {
  name: 'App',
  components: {
    HeaderVue,
    FooterVue,
    Contenido
  }
}
</script>

<style>
@media screen and(max-width:490px){
    nav{
        position:absiluta;
        top:100%;
        left:0;
        background: #232220;
    }
}

</style>
