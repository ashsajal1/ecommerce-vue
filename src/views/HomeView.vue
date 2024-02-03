<script setup lang="ts">
import Card from '@/components/Card.vue';
import Hero from '@/components/Hero.vue';
</script>

<template>
  <main>
    <Hero />
    <div class="p-2 grid grid-cols-3 md:grid-cols-6 gap-2">
      <Card v-for="(item) in 20" :key="item" />
    </div>
  </main>
</template>
