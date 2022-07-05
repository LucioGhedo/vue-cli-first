<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld msg="La mia prima app con Vue CLI!"/>
    <TestCompo msg="Il primo jumbotron component con VUE CLI" personal-msg="doppio msg wow"/>
    <MyCompo test="img"/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import TestCompo from './components/TestCompo.vue'
import MyCompo from './components/MyCompo.vue'

export default {
  name: 'App',
  components: {
    HelloWorld,
    TestCompo,
    MyCompo
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
}
</style>
