<script setup lang="ts">
import { RouterLink, RouterView } from 'vue-router'
import HelloWorld from '@/components/HelloWorld.vue'
</script>

<template>
  <div class="container mx-auto p-4 text-center">
    <h1 class="text-4xl font-bold text-blue-500">Hello Tailwind CSS!</h1>
    <HelloWorld msg="MeoMeo" />
    <nav>
      <RouterLink class="m-5" to="/">Home</RouterLink>
      <RouterLink class="m-5" to="/about">About</RouterLink>
    </nav>
    <RouterView />
  </div>
</template>
