<script setup>
import Concert from './components/Concert.vue'
import Navigation from './components/Navigation.vue'
</script>
<template>
  <div class="m-5">
    <h1 class="text-3xl">
      Hello world!
    </h1>
    <form action="" class="my-10">
      <div class="mb-4">
        <input class="shadow border rounded py-2 px-3 focus:shadow-outline" id="username" type="text"
          placeholder="Username">
      </div>
      <button class="bg-blue-500 hover:bg-blue-700 text-white font-bold py-2 px-4 rounded">
        Button
      </button>

    </form>
  </div>


  <Concert />
</template>
