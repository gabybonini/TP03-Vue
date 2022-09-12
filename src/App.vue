<template>
<div id="app">
  <questao3/>
  <questao4/>
</div>
</template>

<script>

import Questao3 from "@/components/Questao3";
import Questao4 from "@/components/Questao4";

export default {
  name: 'App',
  components: {
    Questao3,
    Questao4,

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
  margin-top: 60px;
}
</style>
