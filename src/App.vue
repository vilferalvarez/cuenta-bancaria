<template>
  <img alt="Vue logo" src="./assets/logo.png">
  <TituloPrincipal texto="Mi banco dinámico 2.0"/>
  <CuentaPrincipal />
</template>

<script>
//import HelloWorld from './components/HelloWorld.vue'
import TituloPrincipal from './components/TituloPrincipal'
import CuentaPrincipal from './components/CuentaPrincipal'
export default {
  name: 'App',
  components: {
    TituloPrincipal,
    CuentaPrincipal
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
