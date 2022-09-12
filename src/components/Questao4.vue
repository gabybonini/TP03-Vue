<template>
  <div>
    <h1>Questão 4</h1>
    <h3>Digite a cor do quadrado no formato #FFFFFF</h3>
    <input type="text" name="cor" id="cor" v-model="cor_back"
    />
    <div class="square" v-bind:style="{ background: cor_back }"></div>
  </div>
</template>

<script>
export default {
  data: function (){
    return {
      cor_back: "#993399",
    };
  },
};
</script>

<style scoped>
.square {
  display: flex;
  align-items: center;
  width: 90px;
  height: 90px;
  border: 1px solid #000;
}
</style>