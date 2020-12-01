<template>
  <div id="app" class="container mt-5">
<!--    <img alt="Vue logo" src="./assets/logo.png">-->
<!--    <HelloWorld msg="Welcome to Your Vue.js App"/>-->
<!--the above used for image display and the HomeWorld is the component -->
  <h1>My Shop</h1>
    <p class="animated fadeInRight">Take a tour at our offerings</p>
  <font-awesome-icon icon="shopping-cart"></font-awesome-icon>
  </div>
</template>

<script>

// import HelloWorld from './components/HelloWorld.vue'
//the above import helps on importing component upon components/HelloWorld.vue
import {FontAwesomeIcon} from "@fortawesome/vue-fontawesome"
export default {
  name: 'App',
  components: {
    // HelloWorld
  FontAwesomeIcon
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
  margin-top: 60px;
}
</style>
