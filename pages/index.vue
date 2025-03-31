<script setup lang="ts"></script>

<template>
  <NuxtLayout name="index-layout">
    <main>
      <RouterLink to="/catalog">go to catalog.</RouterLink>
      <RouterLink to="/home">go home.</RouterLink>
    </main>
  </NuxtLayout>
</template>

<style>
main {
  display: flex;
  flex-direction: column;
  place-items: center;
  padding-right: calc(var(--section-gap) / 2);
}

header {
  display: flex;
  flex-direction: column;
  place-items: center;
  padding-right: calc(var(--section-gap) / 2);
}

.logo {
  margin: 0 2rem 0 0;
}

header .wrapper {
  display: flex;
  place-items: flex-start;
  flex-wrap: wrap;
}
</style>
