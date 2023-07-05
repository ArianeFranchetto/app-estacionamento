<template>
  <div class="home">
    <h1>Estacionamento de Carros</h1>
    <h3>Olá! Seja bem-vindo(a)!</h3>
    <span>Cadastre seu carro &darr; </span>

  </div>

<div>
  <CarroForm/>
</div>
   

 
</template>

<script>
import CarroForm from '@/components/CarroForm.vue';

export default {
  name: 'HomeView',

  components: {
    CarroForm
  }
 
}
</script>

<style>
.home {
  display: flex;
  align-items: center;
  flex-direction: column;
  margin-top: 15px;
}

</style>