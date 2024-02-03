<template>
    <div class="h-[80px] w-[80px] bg-gradient-to-tr absolute from-fuchsia-700 via-fuchsia-400 to-amber-400 blur-3xl -z-10" :class="positon">

    </div>
</template>

<script setup lang="ts">
import { onMounted } from 'vue';

const position = defineProps(['positon']);

onMounted(() => {
    console.log(position)
})
</script>