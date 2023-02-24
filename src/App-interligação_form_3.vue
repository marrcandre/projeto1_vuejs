<script setup>
import { ref } from 'vue'
const texto = ref('Digite seu nome')
</script>

<template>
  <div>
    <input type="text" v-model="texto" />
    <p>Texto digitado: {{ texto }}</p>
  </div>
</template>
