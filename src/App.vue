<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <NewTitle></NewTitle>
    <BonusHero></BonusHero>
  </div>
</template>

<script>
import NewTitle from './components/NewTitle.vue'
import BonusHero from './components/BonusHero.vue'

export default {
  name: 'App',
  components: {
    NewTitle,
    BonusHero
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
