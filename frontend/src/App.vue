<template>
  <div id="app">
    <NesGame />
  </div>
</template>

<script>
import NesGame from './components/NesGame.vue'

export default {
  name: 'App',
  components: {
    NesGame: NesGame
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
