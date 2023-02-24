<script setup>
import { ref } from 'vue'
const texto = ref('Digite seu nome')
</script>

<template>
  <div>
    <input type="text" :value="texto" @input="(event) => (texto = event.target.value)" />
    <p>Texto digitado: {{ texto }}</p>
  </div>
</template>
