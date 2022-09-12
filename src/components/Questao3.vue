<template>
  <div>
    <h1>Questão 3</h1>
    <h3>Digite uma mensagem</h3>
    <input type="text" v-on:input="mensagem = $event.target.value"/>

    <h3>Digite um tamanho de fonte em pixels:</h3>
    <input type="number" v-on:input="fontSize = $event.target.value"/>

    <h3>Digite a cor:</h3>
    <input type="text" v-on:input="color = $event.target.value"/>

    <p>Você digitou:</p>
    <p v-bind:style="{ fontSize: fontSize + 'px', color: color }">
      {{ mensagem }}
    </p>

    <hr/>

  </div>
</template>

<script>
export default {
 data(){
   return {
     color: "blue",
     fontSize: 15,
     mensagem: "",
     background: "",
   };
 }
};
</script>

<style scoped>

</style>