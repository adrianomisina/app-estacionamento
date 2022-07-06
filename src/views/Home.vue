<template>
  <div class="main-container">
   <h1>Cadastro de Veículos</h1>
   <CarroForm/>
  </div>

</template>

<script>
import CarroForm from "../components/CarroForm.vue"
export default {
  name:"Home",
  components: {
    CarroForm
  }
}

</script>

<style scoped>
  
</style>