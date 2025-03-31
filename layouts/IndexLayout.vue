<script>
import "~/assets/reset.css";
</script>
<template>
  <div>
    <NuxtRouteAnnouncer />
    <h2 class="layout__title">Menu</h2>
    <nav class="layout__nav">Navigation</nav>
    <main class="layout__content">
      <slot />
    </main>
    <footer class="layout__footer">Footer</footer>
  </div>
</template>
<style>
.layout__title {
  font-size: 1.5rem;
  font-weight: bold;
}

.layout__nav {
  margin: 1rem 0;
}

.layout__content {
  flex-grow: 1;
  width: 100%;
}

.layout__footer {
  margin-top: 1rem;
  font-size: 0.9rem;
}
</style>
