<template>
  <div id="app">
    <Header />
    <router-view></router-view>
  </div>
</template>

<script>
import Home from './components/Home.vue'
import Header from './components/Header'
import MainArt from './components/MainArt'

export default {
  name: 'app',
  components: {
    Home,
    Header,
    MainArt
  }
}
</script>

<style>
body {
  margin: 0
}

#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>
