<script setup>
import { ref } from 'vue'

const contador = ref(0)

function incrementar() {
  contador.value++
}
</script>

<template>
    <button @click="incrementar">{{ contador }} </button>
</template>