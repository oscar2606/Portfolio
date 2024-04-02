<script setup lang="ts">
const experiences=[
  {
    poste:'Chargé de communication (Alternance)',
    entreprise:'La Maison Des Travaux',
    date:'Du 18/09/23 au 31/08/24'
  },
  {
    poste:'Webdesigner (Stage)',
    entreprise:'Planet Repair',
    date:'Du 20/02/23 au 19/05/23'
  },
  {
    poste:'Chargé de clientèle (Stage)',
    entreprise:'Mimosa Communication',
    date:'Du 07/02/22 au 25/02/22'
  },
  {
    poste:'Conseillé souscription contrat (Emploi saisonnier)',
    entreprise:'La Banque Postale Assurance',
    date:'Du 01/08/19 au 31/08/19'
  }

];

</script>

<template>
    <section id="experience">
  <div class="container">
    <h2>Expériences</h2>
    <div class="experience-list">
      <div class="experience-item" v-for="(exp, index) in experiences" :key="index">
        <h3>{{ exp.poste }}</h3>
        <p>{{ exp.entreprise }}</p>
        <p>{{ exp.date }}</p>
      </div>
    </div>
  </div>
</section>

</template>

<style scoped>
.container{
  background-color:#1E1E1E;
}
.experience-item{
  margin-top: 40px; 
  margin-bottom: 40px;
}
</style>