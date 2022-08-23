<script setup>
  import {
    RouterLink,
    RouterView
  } from 'vue-router'
  import HelloWorld from './components/HelloWorld.vue'
  import Menu from './components/Menu.vue'
</script>

<template>

  <body id="page-top">
    <!-- Navigation-->
    <Menu />
    <!-- Bootstrap core JS-->
    <!-- <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/js/bootstrap.bundle.min.js"></script> -->
    <!-- Core theme JS-->
    <!-- <script src="js/scripts.js"></script> -->
  </body>

  <RouterView />
</template>

<style>

</style>