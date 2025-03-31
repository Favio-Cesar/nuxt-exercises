<script setup lang="ts"></script>

<template>
  <main>
    <RouterLink to="/catalog">Ir a catalog.</RouterLink>
    <RouterLink to="/home">Ir a home.</RouterLink>
  </main>
</template>

<style scoped>
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
