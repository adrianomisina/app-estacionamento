<template>
    
    <footer id="footer">
         <p> Sistema de Estacionamento 2022 &copy; -Adriano Misina </p>

    </footer>     

</template>


<script>

  export default {
      name: "Footer"
  }


</script>

<style scoped>
  #footer {
    height: 80px;
    background-color: #333 ;
    color: #adadad;
    display: flex;
    justify-content: center;
    align-items: center;
    width: 100%;
    bottom: 0;
  }

  p {
    margin-left: 2rem;
  };

</style>