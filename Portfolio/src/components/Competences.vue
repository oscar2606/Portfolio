<script setup lang="ts">
const competences=[
    {
        domaine:'Suite Abode',
        logiciel:'Photoshop, Illustrator, XD'
    },
    {
        domaine:'Maquettage',
        logiciel:'Figma'
    },
    {
        domaine:'CMS',
        logiciel:'Wordpress, Prestashop'
    },
]
</script>

<template>
    <section id="competences">
  <div class="container">
    <h2>Mes compétences</h2>
    <div class="competences-list">
      <div class="competence-item" v-for="(competence, index) in competences" :key="index">
        <h3>{{ competence.domaine }}</h3>
        <p>{{ competence.logiciel }}</p>
      </div>
    </div>
  </div>
</section>

</template>

<style scoped>
.container{
  background-color:#1E1E1E;
  padding: 20px;
}
.competence-item{
  margin-top: 40px; 
  margin-bottom: 40px;
}

</style>