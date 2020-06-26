<template>
  <div id="app">
    <h1>Vue Calculator</h1>
    <Calculator />
  </div>
</template>

<script>
import Calculator from '@/main/Calculator'

export default {
  name: 'App',
  components: { Calculator }
}
</script>

<style>
* {
  margin: 0;
  padding: 0;
  border: 0;
  box-sizing: border-box;
}

html,
body {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}

#app {
  display: flex;
  flex-direction: column;
  height: 100vh;
  justify-content: center;
  align-items: center;
  text-align: center;

  color: #fff;
  background: lightgreen;
}
</style>
