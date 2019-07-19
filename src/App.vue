<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <CountMachine></CountMachine>
  </div>
</template>

<script>
import CountMachine from './components/CountMachine.vue'

export default {
  name: 'app',
  components: {
    CountMachine
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
