<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    
    <HelloWorld msg="Welcome to Your Vue.js App"/>
    <para1 />
    <image1/>
    <banner1/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import para1 from './components/para1.vue'
import image1 from './components/image1.vue'
import banner1 from './components/banner1.vue'

export default {
  name: 'app',
  components: {
    HelloWorld, para1 , image1 , banner1
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
