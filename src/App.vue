<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <viewstest />
  </div>
</template>

<script>
import views from 'views';
import viewstest from 'views/test';
import utils from 'utils';
import test from 'test';

export default {
  name: 'App',
  components: {
    viewstest
  },
  data () {
    return {
      views,
      utils,
      test
    };
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
