<script setup></script>

<template>
  <h1 class="titulo">Formulario:</h1>
  <p>Nome:</p>
  <input type="text" v-model="nome" minlength="10" placeholder="Digite seu nome" />
  <input type="email" v-model="email" minlength="10" placeholder="Digite seu email" />
  <input type="password" v-model="senha" placeholder="Digite sua senha"/>


</template>

<style scoped>

@import url('https://fonts.googleapis.com/css2?family=Mallanna&display=swap');
.titulo {
  text-align: center;
  font-family: 'Mallanna', sans-serif;
}
p {
  font-family: 'Mallanna', sans-serif;
}
</style>
