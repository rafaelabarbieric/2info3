<script setup> 

import {ref }from 'vue'

const contador = ref(0)

</script>

<template>

  <button @click="contador++">+</button>
   <button @click="contador--">-</button>
   <p> Valor do contador: {{ contador }}</p>

</template>

<style scoped> 

button{
  background-color: rgb(104, 104, 250);
  color: white;
  font-weight: bold;
  border: 0;
  margin: 2px;
  padding: 20px;
}

</style>

