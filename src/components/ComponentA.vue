<script setup>

// import {inject} from 'vue';
import {provide} from 'vue';
import ComponentB from './ComponentB.vue'

provide('course-stock',100)
// const course = inject('course')
</script>
 
<template>
    <p>
        <!-- Course Name in Component A: {{ course.name }} -->
        Component A
    </p>
    <p>
        <ComponentB  />
    </p>
</template>
 
<style scoped></style>