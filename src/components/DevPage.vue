<template>
  <div>
    <h1>Hello World</h1>
  </div>
</template>

<script setup>
import { onMounted, onUpdated, ref } from 'vue'

onMounted(() => console.log('DevPage was mounted'))
onUpdated(() => console.log('DevPage was updated'))

</script>
