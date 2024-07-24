<template>
  <HomeCom/>
</template>

<script>
import HomeCom from "@/components/Home.vue"
export default {
  name: 'App',
  components: {
    HomeCom,
  }
}
</script>

<style>
*{
  padding: 0px;
  margin: 0px;
  box-sizing: border-box;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  
  color: #2c3e50;
  
}
</style>
