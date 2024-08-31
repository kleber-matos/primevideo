<template>
  <footer>
    <p>
      © Prime Video © Prime•Video © & ™ Aneis do Poder LTD © 2022 MARVERICK.
      Reservados todos os direitos, Prime Video
    </p>

    <figure>
      <img src="../../assets/image/youtube.svg" alt="Youtube" />
      <img src="../../assets//image/insta.png" alt="Instagram" />
      <img src="../../assets/image/prime.svg" alt="Prime Video" />
    </figure>
  </footer>
</template>

<style scoped>
footer {
  background-color: black;
  display: flex;
  align-items: center;
  justify-content: space-evenly;
  height: 15vh;
  flex-wrap: wrap;
}

figure {
  display: flex;
  justify-content: space-evenly;
  width: 20vw;
  max-width: 200px;

  img {
    width: 5vw;
    max-width: 50px;
  }
}
</style>

<script setup></script>
