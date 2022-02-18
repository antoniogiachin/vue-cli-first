<template>
  <div id="app">
    <newTitle></newTitle>
    <newJumbo></newJumbo>
  </div>
</template>

<script>
import newTitle from './components/newTitle.vue'
import newJumbo from './components/newJumbo.vue'



export default {
  name: 'App',
  components: {
    newTitle,
    newJumbo
  }
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
}
</style>
