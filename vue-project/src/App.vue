<script setup>
import Header from './components/Header.vue';
import Cards from './components/Cards.vue';
import Footer from './components/Footer.vue';
</script>

<template>
  <Header></Header>
  <main>
    <Cards></Cards>
    <Footer></Footer>
  </main>
</template>

<style scoped>
* {
  margin: 0px;
  padding: 0px;
  box-sizing: border-box;
}

main {
  background-color: blanchedalmond;
  height: 100vh;
}

.display-6 {
  font-family: Tahoma, sans-serif;
}
</style>
