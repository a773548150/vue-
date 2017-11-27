<template>
  <div id="app">
    <img src="./assets/logo.png">
    {{ ms }}
    <router-view/>
  </div>
</template>

<script>
export default {
  name: 'app',
  data () {
    return {
      ms: 'hiaocong'
    }
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
