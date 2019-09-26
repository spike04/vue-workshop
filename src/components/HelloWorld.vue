<template>
  <div>
    <div>Hello World - {{message}}</div>
    <p v-text="message" />
  </div>
</template>

<script>
export default {
  name: "HelloWorld",
  data: function() {
    return {
      message: "Vue is awesome"
    };
  }
};
</script>

<style>
</style>