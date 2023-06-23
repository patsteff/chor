<template >
    <div>
        <div v-for="post in posts" :key="'post.id'">
            <h3>{{ post.title }}</h3>
        </div>
    </div>
</template>
<script setup>
import { defineProps } from 'vue'

const props = defineProps({
    posts: Array
})
</script>
<style ></style>