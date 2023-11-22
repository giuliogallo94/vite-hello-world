<script>
export default {
  data() {
    return {
      text: "La mia prima app con Vite!",
    };
  },
};
</script>

<template>
  <h1>{{ text }}</h1>
</template>

<style>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
body {
  background-color: aqua;
  width: 100vw;
  height: 100vh;
  text-align: center;
  line-height: 100vh;
}
</style>
