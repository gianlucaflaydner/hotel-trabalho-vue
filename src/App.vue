<script setup>
import {  RouterView } from 'vue-router'
</script>

<template>



  <header>
    <router-link to="/"><img src="../src/assets/hoteis-chimia.png" alt="teste" /></router-link>
    <h1>CHIMIA HOTÉIS</h1>
  </header>
  
  <RouterView />


  <footer>
    <h2>Since 1909</h2>
  </footer>

</template>


<style scoped>


header {
  height: 100px;
  width: 100%;
  background-color: #d73c3c;
  display: flex;
  align-items: center;
  justify-content: flex-start;
  padding-left: 20px;
}

footer {
  width: 100%;
  height: 100px;
  background-color: #d73c3c;
  display:flex;
  align-items: center;
  justify-content: center;
}

img {
  width: 80px;
  height: 80px;
}


</style>
