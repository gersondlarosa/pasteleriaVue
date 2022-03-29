<template>
<div class="home">
  <Navegador/>
  <Slide/>
  <Card/>
  <Formulario/>
  <Adornos/>
  <Footer/>
</div>

</template>

<script>
// @ is an alias to /src
import Navegador from "../components/navegador.vue";
import Slide from "../components/slide.vue";
import Card from "../components/card.vue";
import Formulario from "../components/formulario.vue";
import Footer from "../components/footer.vue";
import Adornos from "../components/adornos.vue";

export default {
    name: 'HomeView',
    components:{
      Navegador,
      Slide,
      Card,
      Formulario,
      Footer,
      Adornos,

  }
}
</script>
