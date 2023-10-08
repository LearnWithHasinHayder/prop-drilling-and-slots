<script setup>
const props = defineProps(['course'])

</script>
 
<template>
    <p class="ml-10">
        Course Name in Component C: {{ course.name }}
    </p>
    <p class="ml-10">
        <input type="text" v-model="course.name" />
    </p>
</template>
 
<style scoped></style>