<script setup>
import {inject} from 'vue';
const course = inject('course')
const stock = inject('course-stock')
</script>
 
<template>
    <p class="ml-10">
        Course Name in Component C: {{ course.name }}
    </p>
    <p class="ml-10">
        <input type="text" v-model="course.name" />
    </p>
    <p class="ml-10">
        Course Stock : {{ stock }}
    </p>
</template>
 
<style scoped></style>