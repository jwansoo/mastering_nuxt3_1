<script lang="ts" setup>
const firstLesson = useFirstLesson();
</script>

<template>
  <NuxtLink class="underline font-medium" :href="firstLesson.path">
    Go to first lesson
  </NuxtLink>
</template>

<style scoped></style>
