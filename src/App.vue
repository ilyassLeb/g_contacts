<script setup>
import { RouterLink, RouterView } from "vue-router";
import NavbarComponent from "./components/NavbarComponent.vue";
</script>

<template>
   <NavbarComponent />
   <router-view></router-view>



</template>

<style lang="scss">
@use "@/assets/style.scss" as *;
</style>



