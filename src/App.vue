<template>
  <div id="app">
    <Header />
    <Body />
  </div>
</template>

<script lang="ts">
import Vue from "vue";
import Header from "./components/Header.vue";
import Body from "./components/Body.vue";

export default Vue.extend({
  name: "App",
  components: {
    Header,
    Body
  }
});
</script>

<style>
#app {
  font-family: "Nunito Sans", sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  max-width: 1080px;
  margin: 0 auto;
	background-color: sky-blue;
}
</style>
