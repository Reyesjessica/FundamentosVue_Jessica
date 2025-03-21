<script setup>

import HeaderBar from './HeaderBar.vue';

import Menu from './Menu.vue';
import Carosel from './Carosel.vue';

</script>

<template>
  <!-- encabezado  -->
<HeaderBar/>
  <!-- creamos un menu -->
  <Menu/>
 <!-- utilizamos un carrucel -->
 <!--  <Carosel/>
  <!-- un menu de potres -->
  <div class="container my-5">
    <div class="row " style="background-color: #9a928f09; height: 300px;">
      <h3 class="text-center" style="font-family: 'Pincuk - Fuentes Sans' ;font-size: 30px;">Mejores Postres</h3>

      <div class="col-md-4">
        <div class="card" style="border-radius: 5%;">
          <img style="border-radius: 5%; height: 200px;"  src="https://th.bing.com/th/id/OIP.J2ROZtcgXyEGv5b1KEsAbwHaE7?w=626&h=417&rs=1&pid=ImgDetMain" class="card-img-top " alt="Tiramizu">
          <div class="card-img-overlay">
            <p class="card-caption d-none d-md-block" style="color: #d8cfcfcf;text-align:center;font-size: 30px;font-family:George Round;">Tiramisú</p>
          </div>
        </div>
      </div>

      <div class="col-md-4">
        <div class="card" style="border-radius: 5%;">
          <img style="border-radius: 5%; height: 200px; width: 120;"  src="https://th.bing.com/th/id/R.cb0447da9b3b804d353fd2df9a857c15?rik=pSTGoPQpmYpaTQ&riu=http%3a%2f%2fbizcocheando.com%2fwp-content%2fuploads%2f2021%2f03%2fCremaCatalana_7-1024x683.jpg&ehk=zKIcma7B0zvAqmlJX8Jj%2bf0Jc%2fCMCXRdstuta20MOEY%3d&risl=&pid=ImgRaw&r=0" class="card-img-top" alt="Tiramizu">
          <div class="card-img-overlay">
            <p class="card-caption d-none d-md-block" style="color: #fff;text-align: center;font-size: 30px;font-family:George Round;">Crema catalana</p>
          </div>
        </div>
      </div>

      <div class="col-md-4">
        <div class="card" style="border-radius: 5%;">
          <img style="border-radius: 5%; height: 200px;"  src="https://th.bing.com/th/id/OIP.P3dPk1kvx6heWPsI9L-rcQHaEM?rs=1&pid=ImgDetMain" class="card-img-top" alt="Tiramizu">
          <div class="card-img-overlay">
            <p class="card-caption d-none d-md-block" style="color: #d8cfcfcf;text-align: center;font-size: 30px;font-family:George Round;">Cheesecake</p>
          </div>
        </div>
        </div>
        
        </div>
        <center><button type="button" class="btn btn-outline-primary" s>Destacados</button>
        <button type="button" class="btn btn-outline-primary">Mas recientes</button>
        <button type="button" class="btn btn-outline-primary">Mejores Vendidos</button></center>
      </div>
     <!-- seccion -->
  <section class="nosotros my-5">
    
    <div class="container">
      <div class="row">
        <h2 style="font-family: Berlin - Fuentes de Letras Redondas;" > Bienvenidos COFFE </h2>
        <div class="col-md-6">
          <p style="text-align: justify; color: rgb(7, 7, 92);font-size: 18px;">En COFFE, no solo
            servimos café, sino que creamos momentos especiales.
            Nos apasiona ofrecerte una experiencia única, con sabores auténticos y
            una atmósfera acogedora. Desde nuestros granos seleccionados a mano hasta
            las delicadas combinaciones de sabores, cada taza está hecha con amor y dedicación.</p>
        </div>
        <div class="col-md-6">
          <img style=" height: 170px ;width: 450px;" class="img-fluid"
            src="https://th.bing.com/th/id/R.6f5c50013936c54d16e3eb739dab06a4?rik=wFYawKzbTg5hgA&pid=ImgRaw&r=0"
            alt="bebidas">


        </div>
      </div>
    </div>
  </section>
  <!-- OFERTAS con row, card-->

  <section class="OFERTAS my-5">
    <h2 style="font-family:'Times New Roman', Times, serif; color:#320000;" class="text-center my-5"> OFERTAS</h2>
    <div class="container">
      <div class="row">
        <div class="col-md-4">

          <div class="card">
            <img style="height: 250px;"
              src="https://th.bing.com/th/id/OIP.ldsOqbm-2OlaBV01_HCE2QHaEo?rs=1&pid=ImgDetMain" class="card-img-top"
              alt="">
            <div class="card-body text-center">
              <h2 style="color:#4A2C0F; font-family:George Round;"> Nueva bebida</h2>
              <p style="text-align: justify; line-height: 2em;"> Una nueva combinacion de granos de cafe para mejorar el
                sabor y presentacion </p>
              <a href="#" class="btn btn-primary text-center"> Mas Informacion </a>
            </div>
          </div>
        </div>
        <div class="col-md-4">
          <div style="height: 500px;" class="card">
            <img style="height: 250px;"
              src="https://th.bing.com/th/id/OIP.MXZNNAnlldgKSGWDo_06HAHaHX?rs=1&pid=ImgDetMain" class="card-img-top"
              alt="">
            <div class="card-body text-center">
              <h2 style="font-family:George Round;color: #3E1404;"> Café Frappé</h2>
              <p style="text-align: justify; line-height: 2em;"> ¡Un frappé es justo lo que necesitas! Con un rico sabor
                y un dulce aroma. </p>
              <a href="#" class="btn btn-primary text-center"> Mas Informacion </a>
            </div>
          </div>

        </div>
        <div class="col-md-4">
          <div class="card">
            <img style="height:250px ;"
              src="https://th.bing.com/th/id/OIP.NcfUfdhzTMIVJcUGYr1B0gHaLG?rs=1&pid=ImgDetMain" class="card-img-top"
              alt="">
            <div class="card-body text-center">
              <h2 style="font-family: George Round; color:#3E1404; grpu"> Ice Latte</h2>
              <p style="text-align: justify; line-height: 2em;"> Es una bebida deliciosa y refrescante hecha con café
                espresso, leche fría y hielo. </p>
              <a href="#" class="btn btn-primary text-center"> Mas Informacion </a>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>

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
