<script setup>
const props = defineProps(['label']);
</script>
 
<template>
    <button class="bg-gray-500 hover:bg-gray-700 text-white py-2 px-4 rounded">
        <div class="flex items-center" >
            <span>
                {{ label }}
            </span>
        </div>
    </button>
</template>
 
<style scoped></style>