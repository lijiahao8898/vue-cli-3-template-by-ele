<template>
  <div id="app">
    <router-view/>
  </div>
</template>

<script>
export default {
    name: 'app',
    created () {
        this.$nextTick(() => {
        // console.log(this.$route);
        });
    }
};
</script>

<style>
  #app {
    font-family: 'Avenir', Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    color: #2c3e50;
  }
</style>
