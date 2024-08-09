<script setup>
import LoginHeader from './LoginHeader.vue';
</script>

<template>
    <header>
        <h3 class="display-6"><a href="" target="_blank"><i class="bi bi-person-fill-exclamation"></i>Sobre</a></h3>
        <h3 class="display-6"><a href="" target="_blank"><i class="bi bi-house"></i>Home</a></h3>
        <h3 class="display-6"><a href="" target="_blank"><i class="bi bi-whatsapp"></i>Contato</a></h3>
        <LoginHeader></LoginHeader>
    </header>
    
</template>

<style scoped>
header {
    background-color: rgb(97, 12, 104);
    padding: 30px;
    display: flex;
    justify-content: space-around;
}

a {
    color: white;
    text-decoration: none;
}

header .bi { 
  margin-right: 10px;
}
</style>