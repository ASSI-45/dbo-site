<template>
  <HeaderDbo/>
  <BrowseContainer/>
</template>

<script>
import HeaderDbo from './components/HeaderDbo.vue'
import BrowseContainer from './components/BrowseContainer.vue'

export default {
  name: 'App',
  components: {
    HeaderDbo,
    BrowseContainer
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
}
</style>
