<script setup lang="ts">
defineProps<{
  msg: string
}>()
</script>

<template>
  <div>
    <h1 class="text-3xl font-semibold tracking-wider text-orange-700">{{ msg }}</h1>
  </div>
</template>
