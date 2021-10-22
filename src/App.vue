<template>
  <div id="app">
    <!-- <Prueba/> -->
    <!-- <Contacto/> -->
    <Login/>
  </div>
</template>

<script>
//import Prueba from './components/Prueba'
// import Contacto from './components/Contacto'
import Login from './components/Login'

export default {
  name: 'App',
  components: {
    //Prueba,
    //Contacto
    Login
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
