<template>
  <header>
    <h1>
      <img src="@/assets/logo.png" alt="Alura Tracker logo">
    </h1>
  </header>
</template>

<script lang="ts">
import { defineComponent } from 'vue';

export default defineComponent({
  name: 'SidebarComponent',
});
</script>

<style scoped>
header {
  padding: 1rem;
  background: #0D3B66;
  width: 100%;
  height: 100vh;
}

@media only screen and (max-width: 768px) {
  header {
    padding: 2.5rem;
    height: auto;
  }
}
</style>
