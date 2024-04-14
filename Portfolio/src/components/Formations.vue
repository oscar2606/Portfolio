<script setup lang="ts">
const formations=[
    {
        titre:'Bachelor Webdesign (3ème année)',
        école:'MyDigitalSchool Angers',
        date:'18/09/23 - maintenant'
    },
    {
        titre:'Bachelor Digital (3ème année)',
        école:'MyDigitalSchool Angers',
        date:'19/09/22 - 07/07/23'
    },
    {
        titre:'BTS Commerce International à référentiel européen',
        école:'Campus Sacré-Coeur  La Salle (Angers)',
        date:'2019/2021'
    },
    {
        titre:'Bac STMG',
        école:'Lycée Joachim du Bellay (Angers)',
        date:'2019/2021'
    },
]

</script>

<template>
    <section id="formations">
  <div class="container">
    <h2>Formations</h2>
    <div class="formation-list">
      <div class="formation-item" v-for="(formation, index) in formations" :key="index">
        <h3>{{ formation.titre }}</h3>
        <p>{{ formation.école }}</p>
        <p>{{ formation.date }}</p>
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
.formation-item{
  margin-top: 40px; 
  margin-bottom: 40px;
}

</style>