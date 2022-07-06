<template>

  <nav id="nav">
    <router-link to="/" id="logo-url">
        <img :src="logo" :alt="alt" id="">
    </router-link>

    <router-link to="/">Home</router-link> 
    <router-link to="/cadastro">Cadastro</router-link>
  </nav>


</template>


<script>
  export default {
    name:"NavBar",
    props: ["logo", "alt"] //Logo do projeto e as Imagens
  }
</script>

<style scoped>
  #nav {
    background-color: #272a33;
    padding: 15px 50px;
    display: flex;
    justify-content: flex-end;
    align-items: center;
  }

  #nav #logo-url {
    margin: auto;
    margin-left: 0;
  }

  #logo {
    width: 40px;
    height: 40px;
  }

  #logo-url img {
    width: 3.3rem;
  }

  #nav a {
    color: #fff;
    font-weight: bold;
    text-decoration: none;
    margin: 12px;
    transition: .5s;
    font-size: 1.2rem;
    font-family:'Segoe UI', Tahoma, Geneva, Verdana, sans-serif ;
  }

  #nav a:hover {
    color: #3f7fbf;
  }

</style>