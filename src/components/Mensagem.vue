<template>
  <div class="mensagem-container">
    <h3>{{msg}}</h3>
  </div>
</template>

<script>
export default {
  name: "Mensagem",
  props:{
    msg: String,
  }
}
</script>

<style scoped>
  .mensagem-container {
    color: #fff;
    background-color: #002e59;
    width: 25rem;
    text-align: center;
    border-radius: 8px;
    padding: 1rem;
    margin: 1.5rem auto;
  }
</style>