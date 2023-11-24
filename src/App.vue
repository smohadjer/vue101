<template>
  <div>
    <DevPage />
  </div>
</template>

<script setup>
import { onMounted } from 'vue'
import DevPage from '@/components/DevPage.vue'
onMounted(() => console.log('App was mounted'))
</script>
