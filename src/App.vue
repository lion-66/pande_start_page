<script setup>
import { RouterLink, RouterView } from 'vue-router'
import AboutView from './views/AboutView.vue'
import HomeView from './views/HomeView.vue'
</script>

<template>
  <router-link to="/">home</router-link>|
  <router-link to="/about">about</router-link>
  <RouterView />
</template>

<style lang="less" scoped>

</style>
