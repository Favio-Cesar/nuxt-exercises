<script setup lang="ts">
definePageMeta({ layout: "catalog-layout" });
</script>

<template>
  <NuxtLayout name="catalog-layout"
    ><header>
      <h1>Catalog Title</h1>

      <RouterLink to="/home">go home.</RouterLink>
    </header></NuxtLayout
  >
</template>
