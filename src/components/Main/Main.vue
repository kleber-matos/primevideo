<template>
  <main>
    <section>
      <img src="../../assets/image/boys.png" alt="The Boys" />
      <img src="../../assets/image/cris.png" alt="Todos mundo odeia o Chris" />
      <img src="../../assets/image/strela.png" alt="InterStellar" />
    </section>

    <section>
      <img src="../../assets/image/ring.png" alt="Rings of Power" />
      <img src="../../assets/image/big.png" alt="The Big Bang" />
      <img src="../../assets/image/guns.png" alt="Top Guns" />
    </section>
  </main>
</template>

<style scoped>
section {
  display: flex;
  justify-content: space-evenly;
  margin: 2rem 10% 2rem 10%;

  img {
    width: 15vw;
    min-width: 150px;
    height: 45vh;
  }
}
</style>

<script setup></script>
