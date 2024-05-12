<script setup>
import HeaderBar from '@/components/HeaderBar.vue'
import { RouterView } from 'vue-router'

</script>

<template>
  <v-layout>
    <HeaderBar></HeaderBar>
    <RouterView />
  </v-layout>
</template>

<style scoped>

</style>
