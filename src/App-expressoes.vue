<script setup>
const numero = 1
const ok = true
const mensagem = 'Vue3'
</script>

<template>
  {{ Math.pow(numero + 1, 2) }}
  {{ ok ? 'Sim' : 'Não' }}
  {{ mensagem.split('').reverse().join('') }}
</template>

<style scoped>
button {
  font-weight: bold;
}
</style>
