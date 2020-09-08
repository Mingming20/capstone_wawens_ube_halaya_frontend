<template id="background">
  <div id="app">
    <img src="./assets/logo.png">
    <h1>{{ msg }}</h1>
  </div>
</template>

<script>
export default {
  name: 'app',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>

<style lang='scss' scoped>
@import "~assets/color.scss";
body{
    background-image: url("~assets/home.png");
    background-size: cover;
}
</style>
