<script setup>
import {ref} from 'vue'
 const count = ref(0)

 function increment(){
  count.value++
 }
</script>

<template>
<div>
  <button @click="increment">
  count is:{{ count }}
  </button>
</div>
</template>

