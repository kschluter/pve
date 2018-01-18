<template>
  <div id="app">
    <h1>{{ msg }}</h1>
    <el-button>Element Button</el-button>
  </div>
</template>

<script>
export default {
  name: 'app',
  data() {
    return {
      msg: 'Parcel, Vue and Element'
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
