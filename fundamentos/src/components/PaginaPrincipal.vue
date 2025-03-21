<script setup>

import HeaderBar from './HeaderBar.vue';

import Menu from './Menu.vue';
import Carosel from './Carosel.vue';
import cardPostres from './cardPostres.vue';
import seccion from './seccion.vue';
import cardOfertas from './cardOfertas.vue';
import formulario from './formulario.vue';
import piepagina from './piepagina.vue';

</script>

<template>
  <!-- encabezado  -->
<HeaderBar/>
  <!-- creamos un menu -->
  <Menu/>
 <!-- utilizamos un carrucel -->
  <Carosel/>
  <!-- un menu de potres -->
  <cardPostres/>
     <!-- seccion -->
  <seccion/>
  <!-- OFERTAS con row, card-->
   <cardOfertas/>
   <!-- contacto formulario -->
   <formulario/>
<!-- pie de pagina -->
 <piepagina/>
  


</template>

<style scoped>


</style>
