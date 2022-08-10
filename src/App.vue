<template>
  <PinguinGirl name="Glagla"/>
  <img alt="jeune pinguine" src="./assets/images/pinguin.jpeg">
  <PinguinGirl msg="BanquiseBook, le 1er réseau social qui n'a pas froid dans le dos"/>
</template>

<script>
import PinguinGirl from './components/PinguinGirl.vue'

export default {
  name: 'App',
  components: {
    PinguinGirl
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
