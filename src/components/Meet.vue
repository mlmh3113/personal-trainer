<template>
    <div class="flex flex-col  container mx-auto md:grid md:grid-cols-2 gap-4 py-10 dark:bg-gray-900 dark:text-white">

        <div class="w-full col-span-1 ">
            <img class="flex mx-auto object-cover border-2 border-teal-500 p-3 rounded-full w-64 h-64  md:w-96 md:h-96 " src="/img/fitness_11.jpg"
                alt="training_11">
        </div>

        <div class="flex flex-col text-center md:text-start items-center w-full col-span-1 justify-evenly gap-5">
            <h2 class="text-4xl uppercase tracking-widest">Meet <span class="cursive text-teal-500 text-6xl">Personal
                    Fit</span></h2>

            <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Quam architecto doloribus unde, temporibus,
                incidunt sint asperiores similique earum nam magnam ab perferendis! Exercitationem natus officia odit
                excepturi illo similique, magni omnis libero numquam eaque dignissimos eos voluptatibus fugiat qui at?</p>

            <RouterLink to=""><button type="button"
                    class="text-gray-900 bg-white dark:bg-slate-500  uppercase hover:bg-gray-100 border border-gray-200 focus:ring-4 focus:outline-none focus:ring-gray-100 font-medium rounded-lg text-sm px-5 py-2.5 text-center inline-flex items-center dark:focus:ring-gray-600 dark:border-gray-700 dark:text-white dark:hover:bg-gray-700 me-2 mb-2">
                Lear More
            </button></RouterLink>
    </div>
</div></template>

<script setup>
import { RouterLink } from 'vue-router'


</script>

<style scoped></style>