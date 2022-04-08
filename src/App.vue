<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <viewstest />
  </div>
</template>

<script>
import views from '../packages/views';
import viewstest from '../packages/views/test';
import utils from '../packages/utils';
import test from '../packages/test';

console.log(views, utils, test);

export default {
  name: 'App',
  components: {
    viewstest
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
