<script setup>
import { useRoute } from 'vue-router'
import { onMounted } from 'vue'
import { initFlowbite } from 'flowbite'
onMounted(() => {
  initFlowbite();
})
</script>
<template>
  <RouterView />
</template>
