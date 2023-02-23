<script setup>
const rawHtml = '<span style="color: red">Este é um texto em vermelho</span>'
</script>
<template>
  <p>Usando interpolação de textos: {{ rawHtml }}</p>
  <p>Usando v-html: <span v-html="rawHtml"></span></p>
</template>

<style scoped>
button {
  font-weight: bold;
}
</style>
