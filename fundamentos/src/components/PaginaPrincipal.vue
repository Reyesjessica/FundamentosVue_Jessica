<script setup>

import HeaderBar from './HeaderBar.vue';

import Menu from './Menu.vue';
import Carosel from './Carosel.vue';
import cardPostres from './cardPostres.vue';
import seccion from './seccion.vue';
import cardOfertas from './cardOfertas.vue';

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
   <section class="contactenos my-5 ">
    <h2 style="font-family: 'Times New Roman', Times, serif;" class="text-center">Contáctanos</h2>
    <div class="container  " style="height: 500px; width: 500px; ">
      <form action="/submit" method="post "
        style="background-color: rgba(55, 63, 110, 0.719); color: #fff; font-family:'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; font-size: large;">
        <label class="mx-4 my-3" for="name"> Nombre:</label>
        <input type="text" id="name" name="name" required><br><br>

        <label class="mx-4" for="email"> Correo electronico:</label>
        <input type="email" id="email" name="email" required><br><br>

        <label class="mx-4" for="name">Contraseña:</label>
        <input type="text" id="name" name="name" required><br><br>

        <label class="mx-4" for="city"> Ciudad:</label>
        <select name="city" id="city">
          <option value="poo">Mexico</option>
          <option value="ai"> Estados Unidos</option>
        </select> <br><br>
        
          <div class="mb-3 ">
            <label class="mx-4" for="Mensaje"> Mensaje</label>
            <textarea name="mensaje" class="form-control mx-4" id="" cols="30" rows="5"
              style="width: 400px;"></textarea>
          </div>
          <center><button
              style="background-color: rgb(4, 4, 4); color: #f4f8f9; border: black; height: 40px; width: 90px;"
              class="btn-submit my-3" type="submit"> <i class="fas fa-paper-plane"></i>Enviar</button></center>
      </form>
    </div>
  </section>

  
  <footer style="background-color: black; color:#fff;" class="text-center py-3 ">@DWB-Todos los derechos reservados
  </footer>

</template>

<style scoped>


</style>
