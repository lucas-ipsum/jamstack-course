<template>
  <div>
    Hello World
    {{ story }}
  </div>
</template>

<script setup>
const story = await useStoryblok('home', { version: 'draft' })
</script>