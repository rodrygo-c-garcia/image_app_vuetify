<script>
import { RouterLink, RouterView } from 'vue-router'

</script>

<template>
  <div class="about">
    <h1>This is an about page</h1>
    <v-btn depressed color="primary">
      Primary
    </v-btn>
  </div>
</template>

<style>
@media (min-width: 1024px) {
  .about {
    min-height: 100vh;
    display: flex;
    align-items: center;
  }
}
</style>
