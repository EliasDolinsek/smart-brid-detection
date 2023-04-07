<template>
<div class="flex flex-wrap items-center gap-x-44 rounded-lg bg-white border border-gray-400 px-4 py-2">
  <div>
    <p class="text-lg text-black">{{ title }}</p>
    <p class="text-sm font-semibold text-black">{{ subtitle }}</p>
  </div>
  <img :src="imageUrl" alt="Bird image" class="rounded-full w-10 h-10">
</div>
</template>

<script setup>
defineProps({
  title: {
    type: String,
    required: true
  },
  subtitle: {
    type: String,
    required: true
  },
  imageUrl: {
    type: String,
    required: true
  },
})
</script>