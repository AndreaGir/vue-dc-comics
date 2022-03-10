<template>
  <div id="app">
    <MyHeader />
    <MyMain />
    <MyMain2 />
    <MyFooter />
    
    
  </div>
</template>

<script>

import MyHeader from './components/MyHeader.vue'
import MyMain from './components/MyMain.vue'
import MyMain2 from './components/MyMain2.vue'
import MyFooter from './components/MyFooter.vue'

export default {
  name: 'App',
  components: {
    MyFooter,
    MyMain2,
    MyMain,
    MyHeader
  }
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
