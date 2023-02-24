<script setup>
import { ref } from 'vue'
const texto = ref('')
</script>

<template>
  <div>
    <input type="text" v-bind:value="texto" v-on:input="(event) => (texto = event.target.value)" />
    <p>Texto digitado: {{ texto }}</p>
  </div>
</template>
