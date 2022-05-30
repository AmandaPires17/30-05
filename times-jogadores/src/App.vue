<template>
  <header>Home | Jogadore | Times</header>
  <main>Main</main>
  <footer>Rodapé</footer>
</template>

<style>
@import "@/assets/base.css";

#app {
  max-width: 1280px;
  margin: 0 auto;
  /*padding: 2rem; */
  height: 100vh;
  font-weight: normal;
  background-color: pink;
}

header,
footer {
  background-color: purple;
  color: white;
  height: 15%;
  font-size: 1.3rem;
  display: flex;
  align-items: center;
  padding-left: 2rem;
}

main {
  height: 70%;
}
</style>
