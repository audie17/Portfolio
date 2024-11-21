<template>
  <img alt="Vue logo" src="./assets/logo.png">
  <HomeComponent />
  <HelloWorld />
</template>

<script>
import HomeComponent from './components/HomeComponent.vue';
import HelloWorld from './components/HelloWorld.vue';

export default {
  name: 'App',
  components: {
    HomeComponent,
    HelloWorld
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
