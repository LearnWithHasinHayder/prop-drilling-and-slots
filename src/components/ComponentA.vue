<script setup>
// import {course} from '../data/course.js'
import ComponentB from './ComponentB.vue'
const props = defineProps(['course'])
</script>
 
<template>
    <!-- <p>
        Course Name in Component A: {{ course.name }}
    </p> -->
    <p>
        Course A
    </p>
    <p>
        <ComponentB  />
    </p>
</template>
 
<style scoped></style>