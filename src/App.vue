<template>
  <div id="app">
    <mycat value="Number of cats"></mycat>
  </div>
</template>

<script>
import './assets/css/main.css'
import mycat from './components/MyCat.vue'

export default {
  name: 'App',
  components: {
    mycat
  }
}
</script>

<style>
</style>
