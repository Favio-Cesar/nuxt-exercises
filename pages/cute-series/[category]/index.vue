<script setup lang="ts">
const route = useRoute();
const category = route.params.category;
</script>

<template>
  <div>
    <h1>series of the category: {{ category }}</h1>
    <NuxtLink :to="`${category}/spiderman`">watch spiderman episode 1</NuxtLink>
  </div>
</template>

<style lang="css" scoped></style>
