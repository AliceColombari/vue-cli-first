<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <NewTitle></NewTitle>
  </div>
</template>

<script>
import NewTitle from './components/NewTitle.vue'

export default {
  name: 'App',
  components: {
    NewTitle
  }
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
