<script setup>
import {course} from '../data/course.js'
import ComponentC from './ComponentC.vue';
const props = defineProps(['course'])
</script>
 
<template>
    <p class="ml-5">
        Course Name in Component B: {{ course.name }}
    </p>
    <p class="ml-5">
        <ComponentC  />
    </p>
</template>
 
<style scoped></style>