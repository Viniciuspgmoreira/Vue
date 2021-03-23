<template>
  <div id="app">
    <h1>Calculadora</h1>
    <Calculator></Calculator>
  </div>
</template>

<script>
import Calculator from "./main/Calculator.vue";

export default {
  components: { Calculator },
};
</script>

<style>
@font-face {
  font-family: "Oswald", sans-serif;
  src: url("./fonts/Oswald-Regular.ttf");
}

* {
  font-family: "Oswald", sans-serif;
}

body {
  margin: 0;
}

#app {
  display: flex;
  flex-direction: column;
  height: 100vh;
  justify-content: center;
  align-items: center;
  align-content: center;

  color: #fff;
  background: linear-gradient(to right, #0f0c29, #302b63, #24243e);
}
</style>