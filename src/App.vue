<template>
  <div id="app">
    <img src="./assets/logo.png">
    <AccessLevels/>
  </div>
</template>

<script>
import AccessLevels from './components/AccessLevels';

export default {
  name: 'App',
  components: {
    AccessLevels,
  },
};
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
