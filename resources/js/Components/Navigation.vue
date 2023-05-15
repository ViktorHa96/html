<template>

    <div class="flex p-2 px-8 justify-between bg-slate-100 rounded-b-lg border-b-2 ">
        <div class="">
            <Link href="/">Svet Trendov</Link>
        </div>

        <div class="flex gap-4">
            <Link class="px-2 py-1 bg-blue-100 rounded-md shadow-sm shadow-blue-600 border hover:bg-blue-50 hover:border hover:translate-x-0.5 duration-150" href="/posts">Posts</Link>
            <Link class="px-2 py-1 bg-blue-100 rounded-md shadow-sm shadow-blue-600 border hover:bg-blue-50 hover:border hover:translate-x-0.5 duration-150" href="/addpost">Add Post</Link>
        </div>


    </div>
</template>

<script setup lang="ts">
import { Link } from '@inertiajs/vue3';

</script>

<style scoped>

</style>
