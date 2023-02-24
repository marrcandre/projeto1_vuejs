<script setup>
import { ref } from 'vue'

const nome = ref('João')                // string
const idade = ref(30)                   // number
const preco = ref(10.5)                 // number
const ativo = ref(true)                 // boolean
const frutas = ref(['maçã', 'banana'])  // array de strings
const pessoa = ref({                    // objeto
  nome: 'João',
  idade: 30,
  ativo: true
})

const pessoa1 = {                       // objeto não reativo
  nome: 'João',
  idade: 30,
  ativo: true
}
const pessoa2 = {                       // objeto não reativo
  nome: 'Maria',
  idade: 25,
  ativo: true
}

const pessoas = ref([pessoa1, pessoa2])  // array de objetos
</script>

<template>

  <p>{{ nome }}  </p>
  <p>{{ idade }} </p>
  <p>{{ preco }} </p>
  <p>{{ ativo }} </p>
  <p>{{ frutas }} </p>
  <p>{{ pessoa }} </p>
  <p>{{ pessoas }} </p>
</template>
