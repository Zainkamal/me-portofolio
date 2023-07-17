<script setup>
import { RouterLink, RouterView } from "vue-router";
//import HelloWorld from "./components/HelloWorld.vue";
import navbar from "./components/MenuItem.vue";
import Footer from "./components/Footer.vue";
</script>

<template>
  <div class="d-flex">
    <navbar></navbar>
    <RouterView />
  </div>
  <Footer></Footer>
</template>

<style scoped></style>
