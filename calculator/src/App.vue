<template>
  <div id="app">
   <HeadingComp/>
    <CalculatorComp/>
  </div>
</template>

<script>
import HeadingComp from './components/HeadingComp.vue';
import CalculatorComp from './components/CalculatorComp.vue';

export default {
  name: "App",
  components: {
    HeadingComp,
    CalculatorComp
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 30px;
}
</style>
