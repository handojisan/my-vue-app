<template>
  <div id="app">
    <div>良い感じのタイトル</div>
    <div>すごい機能をつけました</div>
    <Counter></Counter>
    <img alt="Vue logo" src="./assets/logo.png" />
    <HelloWorld msg="Welcome to Your Vue.js App" />
  </div>
</template>

<script>
import HelloWorld from "./components/HelloWorld.vue";
import Counter from "@/components/Counter.vue";

export default {
  name: "App",
  components: {
    HelloWorld,
    Counter,
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
