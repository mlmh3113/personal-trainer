<script setup>
import { RouterView } from 'vue-router'
import Header from './components/Header.vue'



</script>

<template >

<Header />

<main class="mx-auto">
    <RouterView />
</main>

</template>

<style>
.cursive {
    font-family: "Grape Nuts", cursive;
}

</style>
