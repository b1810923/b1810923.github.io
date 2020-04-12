<template>
  <div id="app">
    <v-facebook-login app-id="1706489239614542"></v-facebook-login>
    <img alt="Vue logo" src="./assets/logo.png">
  </div>
</template>
<script src="https://unpkg.com/vue-facebook-login-component/dist/vueFacebookLoginComponent.umd.min.js"></script>
<script>
import VFacebookLogin from 'vue-facebook-login-component'
export default {
  name: 'App',
  components: {
    VFacebookLogin
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
