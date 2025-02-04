<script setup lang="ts">
// import TheWelcome from '../components/TheWelcome.vue'
</script>

<template>
  <main>
    <h2>This home View</h2>
    <router-link to="/projects">Go To Projects Page</router-link>
    <router-link :to="{ name: '/projects/[id]', params: { id: 1 } }">Go To Project 1</router-link>
    <!--TheWelcome /-->
  </main>
</template>
