<template>
    <header class="flex h-[60px] items-center justify-between p-2">
        <RouterLink to="/" class="text-lg text-fuchsia-700 font-bold">Logo</RouterLink>
        <div class="flex items-center justify-between gap-2">
            <RouterLink to="/explore" class="btn-outline">Explore</RouterLink>
            <RouterLink to="/signup" class="btn">Sign up</RouterLink>
        </div>
    </header>
</template>

<script setup lang="ts">
import { RouterLink } from 'vue-router';
</script>