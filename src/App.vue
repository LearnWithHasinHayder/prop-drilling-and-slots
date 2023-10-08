<script setup>
import { ref, reactive } from 'vue';
import Button from './components/Button.vue';
</script>

<template>
  <div class="container mx-auto">
    <div class="flex items-center mt-5">
      <img class="logo" src="./assets/vue.svg" alt="Vue logo" />
      <h1 class="text-2xl">Prop Drilling & Slots</h1>
    </div>

    <div class="mt-10">
      <p>
        Lorem ipsum dolor sit amet, consectetur adipisicing elit. Voluptates, nostrum accusantium earum tempora dolorem ad voluptatibus nemo dolorum totam delectus.
      </p>
    </div>

    <div class="mt-10">
      <label>Components</label><br />
      <p class="mt-5">
        <Button>
          
          <template v-slot:licon>
            <svg height="20" viewBox="0 0 128 128" width="20" xmlns="http://www.w3.org/2000/svg" id="fi_4208490">
            <g>
              <circle cx="64.001" cy="63.999" fill="#f24646" r="45"></circle>
              <path d="m54.44 84.253 31.788-18.353a2.195 2.195 0 0 0 0-3.8l-31.788-18.355a2.2 2.2 0 0 0 -3.293 1.9v36.707a2.2 2.2 0 0 0 3.293 1.901z" fill="#fffcee"></path>
            </g>
          </svg>
          </template>
          Dont Click Me
          <template v-slot:ricon>
            <svg height="20" viewBox="0 0 128 128" width="20" xmlns="http://www.w3.org/2000/svg" id="fi_4208490">
            <g>
              <circle cx="64.001" cy="63.999" fill="#f24646" r="45"></circle>
              <path d="m54.44 84.253 31.788-18.353a2.195 2.195 0 0 0 0-3.8l-31.788-18.355a2.2 2.2 0 0 0 -3.293 1.9v36.707a2.2 2.2 0 0 0 3.293 1.901z" fill="#fffcee"></path>
            </g>
          </svg>
          </template>
        </Button>
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
}</style>
