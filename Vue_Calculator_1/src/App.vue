<template>
  <div id="app">
    <h1>Simple Calculator</h1><Calculator />
  </div>
</template>

<script>
import Calculator from "./main/Calculator"


export default {
  name: 'App',
  components: {
    Calculator
  }
}
</script>

<style>
@font-face {
  font-family: "Oswald";
  src: url("./fonts/Oswald.ttf");
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
  text-align: center;
  background: linear-gradient(to right, rgb(83,105,118), rgb(41,46,73));
  font-family: "Oswald";
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #ffffff;
 
}

</style>
