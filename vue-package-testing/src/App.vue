<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png" />
    <HelloWorld msg="Welcome to Your Vue.js App" />
    <VueElegentButton />
    <RedButton />
    <GitVueElegentButton />
    <GitRedButton />
  </div>
</template>

<script>
import HelloWorld from "./components/HelloWorld.vue";
import {
  RedButton,
  VueElegentButton,
} from "@scm-saw-kyaw-myint/vue-package-button/dist/button/DesignButton.umd";

import {
  RedButton as GitRedButton,
  VueElegentButton as GitVueElegentButton,
} from "vue-package-button/dist/button/DesignButton.umd";

export default {
  name: "App",
  components: {
    HelloWorld,
    VueElegentButton,
    RedButton,
    GitRedButton,
    GitVueElegentButton,
  },
};
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
