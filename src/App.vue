<template>
  <div id="app">
    <headerComponent class="header-component"/>
    <main-component/>
  </div>
</template>

<script>
import headerComponent from './components/headerComponent.vue';
import MainComponent from './components/mainComponent.vue';


export default {
  name: 'App',
  components: {
    headerComponent,
    MainComponent
}
}
</script>

<style>
  @import '../node_modules/bootstrap';
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
 
}

.header-component{
height: 600px;
}
</style>
