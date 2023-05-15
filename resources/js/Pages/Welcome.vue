<script setup lang="ts">
import { Head, Link } from '@inertiajs/vue3';
import Navigation from '../Components/Navigation.vue'

</script>

<template>
    <Head title="Welcome" />
    <Navigation/>

    <div class="center-screen">
        <h1 class="font-bold text-2xl">Vitaj vo Svete Trendov!</h1>
        <ul class="flex flex-col gap-2 my-4">
            <li>Uč sa nové veci</li>
            <li>Pridávaj posty</li>
            <li>Edituj</li>
            <li>Vymazuj</li>
            <li>Pracuj s Databázou</li>
            <li>Makaj na sebe!</li>
        </ul>
    </div>

</template>

<style>
.center-screen {
    position: absolute;
      top: 50%;
      left: 50%;
      margin-right: -50%;
      transform: translate(-50%, -50%);
      text-align: center;
      background-color: aliceblue;
      padding: 2rem;
      border-radius: 2rem;
      border: 2px solid black;
      box-shadow: 4px 6px gray;
}
</style>
