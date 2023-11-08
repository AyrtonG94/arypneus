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
  height: 130px;
}

.logo-containner {
  display: flex;
  justify-content: center;
}

.logoary {
  height: 350px;
}

.pneu {
  margin-top: 80px;
}


</style>
