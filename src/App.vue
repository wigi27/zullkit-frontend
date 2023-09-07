<script setup>
import { RouterView } from "vue-router";
import Navbar from "./components/layouts/Navbar.vue";
import HelloWorld from "./components/example/HelloWorld.vue";
</script>

<template>
  <Navbar />
  <RouterView />
</template>

<style>
@import "@/assets/css/styles.css";
</style>
