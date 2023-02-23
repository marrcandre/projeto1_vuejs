<script setup>
const mensagem = 'Vue3'

function inverter(texto) {
  return texto.split('').reverse().join('')
}
</script>

<template>
  <p>{{ inverter(mensagem) }}</p>
</template>

<style scoped>
button {
  font-weight: bold;
}
</style>
