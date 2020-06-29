<template>
  <div id="app">
    <img src="./assets/logo.png">
    <a-button type="primary">登录</a-button>
    <router-view/>
  </div>
</template>

<script>
import { Button } from 'ant-design-vue'
export default {
  name: 'App',
  components: {
    Button
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
