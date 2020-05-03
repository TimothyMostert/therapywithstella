<template>
  <div id="app">
    <router-view/>
    <nav-bar></nav-bar>
  </div>
</template>

<script>
import NavBar from "@/components/Nav.vue";
export default {
  name: "App",
    components: {
    NavBar
  }
}
</script>

<style lang="scss">
@import "@/assets/styles/settings.scss";
html, body {
  margin: 0;
  padding: 0;
}

#app {
  -webkit-font-smoothing: antialiased;
}
</style>
