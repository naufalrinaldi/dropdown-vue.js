<template>
  <div id="app">
    <dropdown />
  </div>
</template>

<script>
import Dropdown from './components/Dropdown.vue';

export default {
  name: 'App',
  components: {
    Dropdown,
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: left;
  color: #2c3e50;
  margin-top: 0px;
}
</style>
