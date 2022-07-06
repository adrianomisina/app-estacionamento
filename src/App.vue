<template>
  <NavBar :logo="logo_src" :alt="app_name"/>
  <router-view/>  <!--  As viwes são impresas atraves deste carinha  -->
  <Footer />
</template>

<script>
  import NavBar from '@/components/NavBar'
  import Footer from '@/components/Footer'
  
export default {
  name:"App",
  components: {
    NavBar,
    Footer
  },

  data() {
    return {
      logo_src:"/img/carro.png",
      app_name:"Cadastre seu Carro no Estacionamento."
    }
  }
}
</script>

<style>
  *{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family:'Segoe UI', Tahoma, Geneva, Verdana, sans-serif ;
  }

  body {
    background-image: url("../public/img/parking.jpg");
    background-size: cover;
    background-position: center;
    background-repeat: no-repeat;
  }

  .main-container {
    margin: 40px;
    min-height: 82vh;
  }

  h1 {
    text-align: center;
    font-size: 42px;
    margin-bottom: 2rem;
    color: #adadad;
  }
</style>