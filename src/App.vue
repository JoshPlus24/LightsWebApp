<template>
  <div id="app">
    <HelloWorld msg="Sainsburies Lights"/>
    <Navigation/>
  </div>
</template>

<script>
import HelloWorld from "./components/home.vue";
import Navigation from "./components/navigation.vue";

export default {
  name: "App",
  components: {
    HelloWorld,
    Navigation
  }
};
</script>

<style>
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

button {
  box-shadow: unset;
  border: unset;
  font-size: 5vw;
  border-radius: 5px;
}
</style>
