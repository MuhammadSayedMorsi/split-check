<template>
  <div>
    <Header />
  <router-view></router-view>
  </div>
</template>

<script>
// import HelloWorld from "./components/HelloWorld.vue";
import Header from './Header'

export default {
  name: "App",
  components: {
    // HelloWorld,
    Header
  },
};
</script>
<style lang="sass" scoped>
nav
  font-size: 20px
  a
    display: inline-block
    background: pink
    margin: 20px
    marign-top: 20px
</style>