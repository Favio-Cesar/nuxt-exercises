<script setup lang="ts"></script>

<template>
  <header>
    <h1>Titulo home</h1>
    <RouterLink to="/catalog">Ir a catalog.</RouterLink>
  </header>
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
