<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <WelcomePlayer msg="Welcome to RPSLS Duel"/>
    <WelcomePlayer player="Play with Person"/>
    <WelcomePlayer player="Play with Computer"/>
  </div>
</template>

<script>
import WelcomePlayer from './components/WelcomePlayer.vue'

export default {
  name: 'app',
  components: {
    WelcomePlayer
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
