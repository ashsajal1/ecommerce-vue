<template>
    <div class="flex items-center justify-center flex-col gap-2 p-12">
        <h1 class="text-2xl md:text-3xl font-bold bg-gradient-to-tr from-fuchsia-700 to-amber-400 bg-clip-text text-transparent">Welcome
            to E-Commerce shop</h1>
        <p>Buy products with huge discounts!</p>
        <div class="flex gap-2 mt-3">
            <button class="btn-outline">Create an account</button>
            <button class="btn">Explore</button>
        </div>

        <BlobItem positon="left-0" />
        <BlobItem positon="right-0" />
        <BlobItem positon="left-1/2" />
    </div>
</template>

<script setup lang="ts">
import BlobItem from '../components/BlobItem.vue'
</script>