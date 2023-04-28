<template>
  <div id="app">
    <Ad_pc/>
    <List_pc/>
  </div>
</template>

<script>
import Ad_pc from '@/components/Ad_pc'
import List_pc from '@/components/List_pc'

export default{
  
  name: 'App',
  components: {
    Ad_pc,
    List_pc
  }
}
</script>

<style>

body{
  margin: 0;
  padding: 0;
  background-color: #1D203E;;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>
