<template>
  <div id="app">
    <Formulario/>
  </div>
</template>

<script>
import Formulario from './components/Formulario.vue'

export default {
  name: 'App',
  components: {
    Formulario
  }
}
</script>

<style>
  body{
    margin: 0;
    padding: 0;
    height: 100vh;
    display: flex;
    flex-direction: column;
    background-image: url('assets/bg-intro-mobile.png');
    background-color: #ff7978;
    box-sizing: border-box;
  }
</style>
