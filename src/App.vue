<script setup>
import { ref, reactive } from 'vue';
import ComponentA from './components/ComponentA.vue';
import { course } from './data/course.js';

</script>

<template>
  <div class="container mx-auto">
    <div class="flex items-center mt-5">
      <img class="logo" src="./assets/vue.svg" alt="Vue logo" />
      <h1 class="text-2xl">Prop Drilling & Slots</h1>
    </div>

    <div class="mt-10">
      Course name: {{ course.name  }}
    </div>

    <div class="mt-10">
      <label >Components</label><br />
      <p class="mt-5">
        <ComponentA />
      </p>
    </div>
  </div>
</template>

<style scoped>
.logo {
  height: 6em;
  padding: 1.5em;
  padding-left: 0;
  will-change: filter;
  transition: filter 300ms;
}

.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}

.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}
</style>
