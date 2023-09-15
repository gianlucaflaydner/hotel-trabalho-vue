<script setup>

</script>

<template>
  <main>
    <div class="card">
      <h1 class="titulo">Reservar um quarto</h1>
      <img src="../assets/imagem-quarto.jpg" alt="quarto de hotel" class="imagem"/>
      <router-link to="/reserva" class="router-link"><button class="botao"> Reservar</button></router-link>
    </div>
    <div class="card">
      <h1 class="titulo">Checkin</h1>
      <img src="../assets/imagem-recepcao.jpg" alt="quarto de hotel" class="imagem"/>
      <router-link to="/checkin" class="router-link"><button class="botao">Checkin</button></router-link>
    </div>
    <div class="card">
      <h1 class="titulo">Checkout</h1>
      <img src="../assets/imagem-checkout.jpg" alt="quarto de hotel" class="imagem"/>
      <router-link to="/checkout" class="router-link"><button class="botao">Checkout</button></router-link>
    </div>
  </main>
</template>

<style>

main {
  display: flex;
  width: 100%;
  height: 100%;
  align-items: center;
  justify-content: center;
  gap: 60px
}


.card{
  height: 450px;
  background-color: rgba(243, 233, 220, 0.518);
  width: 250px;
  display: flex;
  align-items: center;
  flex-direction: column;
  justify-content: center;
  border: 2px solid rgb(91, 91, 91);
  border-radius: 20px;
}

.titulo{
  font-size:26px;
  color: rgb(27, 26, 26);
  font-weight: bold;
  text-align: center;
  
}
.imagem {
  width: 95%;
  height: 150px;
  border-radius: 5px;
  border: 1px solid black;
  margin-top: 20px;
  margin-bottom:20px;
}

.botao {
  width: 70%;
  height: 50px;
  padding: 10px 10px 10px 10px;
  background-color: rgb(84, 84, 238);
  color: white;
  border-radius: 20px;

}

.router-link{
  width: 100%;
  display:flex;
  align-items: center;
  justify-content: center;
  cursor: pointer;
}
</style>
