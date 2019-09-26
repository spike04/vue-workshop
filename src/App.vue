<template>
  <div>
    <div id="app">Getting started with Vuejs</div>
    <HelloWorld />
  </div>
</template>

<script>
import HelloWorld from "./components/HelloWorld";

export default {
  components: { HelloWorld },
  name: "app"
};
</script>

<style lang="scss">
@import "./styles/main.scss";

#app {
  margin-top: 60px;
}
</style>
