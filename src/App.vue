<template>
  <img
    alt="Vue logo"
    src="./assets/logo.png"
  >
  <MonacoEditor />
</template>

<script>
import MonacoEditor from "./components/MonacoEditor.vue";

export default {
  name: "App",
  components: {
    MonacoEditor
  }
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
