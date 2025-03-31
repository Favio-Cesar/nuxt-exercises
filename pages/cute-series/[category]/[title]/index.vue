<script setup lang="ts">
const route = useRoute();
const title = route.params.title;
const category = route.params.category;
</script>

<template>
  <span>
    <h1>You're currently watching {{ title }}</h1>
    <h2>with this category : {{ category }}</h2>
  </span>
</template>

<style lang="css" scoped></style>
