<script setup lang="ts">
import { RouterLink, RouterView } from 'vue-router'
import HelloWorld from './components/HelloWorld.vue'
import Hero from '@/components/Hero.vue'
import  Experiences from '@/components/Experiences.vue'
import Formations from '@/components/Formations.vue'
import Competences from '@/components/Competences.vue'
import Projets from '@/components/Projets.vue'
import Contact from '@/components/Contact.vue'
</script>

<template>
  <Hero/>
  <Experiences/>
  <Formations/>
  <Competences/>
  <Projets/>
  <Contact/>
</template>

<style scoped>
section {
  margin-top: 80px;
  margin-bottom: 80px;
  
}
</style>
