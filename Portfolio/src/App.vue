<script setup lang="ts">
import { RouterLink, RouterView } from 'vue-router'
import HelloWorld from './components/HelloWorld.vue'
import Hero from '@/components/Hero.vue'
import  Experiences from '@/components/Experiences.vue'
</script>

<template>
  <Hero/>
  <Experiences/>
</template>

<style scoped>
section {
  margin-top: 80px;
  margin-bottom: 80px;
}
</style>
