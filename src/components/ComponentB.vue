<script setup>
import {inject} from 'vue';
import ComponentC from './ComponentC.vue';

const course = inject('course')
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