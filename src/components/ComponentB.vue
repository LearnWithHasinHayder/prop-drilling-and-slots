<script setup>
import ComponentC from './ComponentC.vue';
const props = defineProps(['course'])
</script>
 
<template>
    <p class="ml-5">
        Course Name in Component B: {{ course.name }}
    </p>
    <p class="ml-5">
        <ComponentC :course="course" />
    </p>
</template>
 
<style scoped></style>