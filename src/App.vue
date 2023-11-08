<script setup>

import PromoComponent from './components/PromoComponent.vue';
import PneuComponent from './components/PneuComponent.vue';

</script>

<template>
  <header class="topo">

    <section class="logo-containner">
      <img src="@/assets/Logo.png" class="logoary">
    </section>

  </header>

  <section class="promo">
    <PromoComponent></PromoComponent>
  </section>


  <section class="pneu">
    <PneuComponent></PneuComponent>
  </section>
 
  <footer>
    <div class="footer-container">
      <div class="footer-section">
        <h2>Sobre</h2>
        <p>Referência de preço e qualidade em todo o Brasil.</p>
      </div>
      <div class="footer-section">
        <h2>Links Úteis</h2>
        <ul>
          <li><a href="#">Página Inicial</a></li>
          <li><a href="#">Produtos</a></li>
          <li><a href="#">Contato</a></li>
        </ul>
      </div>
      <div class="footer-section">
        <h2>Contato</h2>
        <p>Endereço:  Jardim Portugalia, Suzano - SP, 08613-135</p>
        <p>Email: contato@arypneus.com</p>
        <p>Telefone: (11) 3924-5570</p>
      </div>
    </div>
  </footer>
</template>

<style scoped>
body {
  margin: 0;
  padding: 0;
}

.promo {
  display: flex;
  flex-direction: column;
  background-color: black;
  height: 132px;
}

.logo-containner {
  display: flex;
  justify-content: center;
}

.logoary {
  height: 351px;
}

.pneu {
  margin-top: 80px;
}


/* Estilos para o footer */
footer {
  background-color: #333;
  color: #fff;
  padding: 20px 0;
}

.footer-container {
  display: flex;
  justify-content: space-around;
  flex-wrap: wrap;
}

.footer-section {
  flex: 1;
  text-align: center;
  margin: 0 20px;
}

.footer-section h2 {
  font-size: 18px;
  margin-bottom: 10px;
}

ul {
  list-style: none;
  padding: 0;
}

ul li {
  margin-bottom: 5px;
}

a {
  color: #fff;
  text-decoration: none;
}

/* Estilos responsivos */
@media (max-width: 768px) {
  .footer-container {
    flex-direction: column;
  }

  .footer-section {
    flex: none;
    margin: 10px 0;
  }
}


</style>
