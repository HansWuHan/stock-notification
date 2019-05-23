<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <NewItem/>
  </div>
</template>

<script>
import NewItem from './components/NewItem/NewItem.vue'

export default {
  name: 'app',
  components: {
    NewItem
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
