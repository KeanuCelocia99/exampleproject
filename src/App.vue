<template>
  <div id="app">
<TestFile></TestFile>
</div>
</template>

<script>
import TestFile from './components/TestFile.vue'

export default {
  name: 'App',
  components: {
    TestFile
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
