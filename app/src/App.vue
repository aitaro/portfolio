<template>
  <div id="app">
    <div class="container">
      <Top />
      <Profile />
      <Works />
    </div>
  </div>
</template>

<script>
import Top from './components/Top.vue'
import Profile from './components/Profile.vue'
import Works from './components/Works.vue'

export default {
  name: 'App',
  components: {
    Top,
    Profile,
    Works
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
.container {
  overflow: auto;
  scroll-snap-type: y mandatory;
  height: 100vh;
}
</style>
