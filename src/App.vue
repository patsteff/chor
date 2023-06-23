<template>
  <Navigation />
  <div class="m-20">
    <h1 class="text-3xl">
      Hello world!
    </h1>
    <form action="" class="my-10">
      <div class="mb-4">
        <input class="shadow border rounded py-2 px-3 focus:shadow-outline" id="username" type="text" placeholder="To Do">
      </div>
      <button class="bg-blue-500 hover:bg-blue-700 text-white font-bold py-2 px-4 rounded">
        Add
      </button>

    </form>
    <div class="shadow border rounded p-2 my-5" v-for="i in 3">
      <div class="flex justify-between">
        <div class="card-content py-2">Housework</div>
        <div>
          <button class="bg-red-500 hover:bg-red-700 text-white py-2 px-4 rounded ml-2">Delete</button>
          <button class="bg-green-500 hover:bg-green-700 text-white py-2 px-4 rounded ml-2">Done</button>
        </div>

      </div>

    </div>

  </div>
  <PostList :posts="posts" />


  <Concert />
</template>
<script setup>
import { ref } from 'vue';
import Concert from './components/Concert.vue';
import PostList from './components/PostList.vue';
import Navigation from './components/Navigation.vue';
const posts = ref([
  { title: 'Welcome to the Blog', body: 'Das ist ein erste Post', id: 1 },
  { title: 'Top Tipps', body: 'Top 5 Konzerte im 2023', id: 1 },

])

</script>
<style></style>