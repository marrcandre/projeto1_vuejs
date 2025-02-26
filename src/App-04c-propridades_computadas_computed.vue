<script setup>
import { ref, computed } from 'vue'

const professor = ref({
  nome: 'Marco André Mendes',
  disciplinas: ['Desenvolvimento Web III', 'Projeto Integrador III']
  //   disciplinas: []
})

const possuiDisciplinas = computed(() => {
  return professor.value.disciplinas.length > 0 ? 'Sim' : 'Não'
})
</script>

<template>
  <div>
    <h1>Professor</h1>
    <p>Nome: {{ professor.nome }}</p>
    <p>Possui disciplinas: {{ possuiDisciplinas }}</p>
    <p>Disciplinas: {{ professor.disciplinas }}</p>
  </div>
</template>
