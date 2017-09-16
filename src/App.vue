<template>
  <div id="app">
  <!-- <router-link v-bind:to="'/'">Home</router-link>
  <router-link v-bind:to="'/about'">About</router-link>
  <router-link v-bind:to="'/param'">Param Link</router-link> -->
  <!-- the router outlet, where all matched components would ber viewed -->
  <router-view></router-view>
  <md-bottom-bar md-shift>
  <md-bottom-bar-item md-icon="history" md-active><router-link v-bind:to="'/'">Home</router-link></md-bottom-bar-item>
  <md-bottom-bar-item md-icon="favorite"><router-link v-bind:to="'/about'">About</router-link></md-bottom-bar-item>
  <md-bottom-bar-item md-icon="near_me"><router-link v-bind:to="'/param'">Param Link</router-link></md-bottom-bar-item>
</md-bottom-bar>
  </div>
</template>

<script>
export default {
  name: 'app',
}
</script>
<!-- styling for the component -->
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
