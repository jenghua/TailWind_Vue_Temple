<template>
  <div id="app">
    <mycat value="Number of cats"></mycat>
  </div>
</template>

<script>
import './assets/css/main.css'
import helloWorld from './components/HelloWorld.vue'
import mycat from './components/MyCat.vue'

export default {
  name: 'App',
  components: {
    helloWorld,
    mycat
  }
}
</script>

<style>
</style>
