<script setup>

import BTN from "./BTN.vue";
import IconLaptop from "./icons/IconLaptop.vue";

</script>

<template>


  <div class="container-fluid">

    <img class="back size position-relative start-25 withbackgound" src="/trafico-web.png">
    <h1 class="">Inicio de sesión</h1>
    <div class="border border-warning">
      <div class="margen">
      <p class="form-label ">Usuario</p>
      <input class="form-control" >
      <br>
      <p class="form-label">Contraseña</p>
      <input type="password" class="form-control">
      <br>
      <b-t-n class="position-relative"></b-t-n>
      </div>
    </div>
  </div>
</template>

<style scoped>
  .margen{
    margin: 5%;
  }
  .back{
    background-color: white;
  }
  .size{
    width: 25%;
  }
  .start-25{
    margin-left: 35%;
  }
  .withbackgound{
    background-color: transparent;
  }
</style>
