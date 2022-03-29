<template lang="html">

  <Navegador/>
  <Pedidos/><br><br><br><br><br><br><br><br><br><br><br><br><br><br>

  <Footer/>


</template>


<script>
// @ is an alias to /src
import Navegador from "../components/navegador.vue";
import Pedidos from "../components/pedidosComponent.vue";
import Footer from "../components/footer.vue";


export default {
    name: 'HomeView',
    components:{
      Navegador,
      Footer,
      Pedidos,
      }
}
</script>

<style media="screen">
footer{
  padding: 1em 0;
  background-color: #38b3f4;
  max-height: 100%;
  max-width: 100%;
  margin-top:auto;

}
body{
  margin: 0;
  display: flex;
  flex-direction: column;
  min-height: 100vh;
}
</style>
