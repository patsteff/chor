<template>
    <div>
        <h3>{{ post.title }}</h3>
        <p>{{ post.body }}</p>
    </div>
</template>
<script setup>
const props = defineProps({
    post: Object
})
</script>
<style></style>