<script setup lang="ts">
defineProps({ text: String })
</script>

<template>
  <h1 class="font-semibold font-inter xl:text-4xl lg:text-3xl">{{ text }}</h1>
</template>
