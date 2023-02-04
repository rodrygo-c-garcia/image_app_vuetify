<script setup>
import SideBar from './views/SideBar.vue';
</script>
<template>
  <v-app>
    <!-- Sidebar -->
    <SideBar />
    <v-main>
      main
    </v-main>
  </v-app>
</template>

<!-- <template>
  Con Rutas
  <div>
    <nav>
      <RouterLink to="/">Home</RouterLink>
      <RouterLink to="/about">About</RouterLink>
    </nav>
  </div>
  <RouterView />
</template> -->