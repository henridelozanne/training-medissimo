<template>
  <div id="app">
    <h1>Training</h1>
    <el-input v-model="test"></el-input>
    <FirstTable />
  </div>
</template>

<script>
import FirstTable from './components/FirstTable'

export default {
  name: 'app',
  data() {
    return {
      test: undefined,
    };
  },
  components: {
    FirstTable
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
