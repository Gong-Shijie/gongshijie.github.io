<template>
  <div id="app">
    <div id="main">
    <router-view></router-view>
    </div>
  </div>
</template>

<script>
export default {
  name: 'App'
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
  width: 100%;
  height: 100%;
}

body {
    background-color: whitesmoke;
}

#main {
  overflow: hidden;
  margin: auto;
}
#body {
  margin-top: 80px;
  width: 80%;
  height: 800px;
  margin-left: 10%;
  background: white;
}
  #left_menu {
    float: left;
    width: 240px;
    height: 800px;
    margin-right: 80px;
    text-align: center;
  }

#right_content {
padding: 40px;
}
</style>
