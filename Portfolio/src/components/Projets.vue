<script setup lang="ts">

</script>

<template>
   <section id="projets">
  <div class="container">
    <h2 class="section-title">Mes Projets</h2>
    <div class="projects-container">
      <div class="project">
        <h3 class="project-title">Rédaction de contenus/référencement</h3>
        <img src="/Users/oscarperrault/Library/Mobile Documents/com~apple~CloudDocs/Documents/Portfolio B3 Webdesign/Visuel-blog-JS-6.png" alt="Image Projet 1">
        <a href="#" class="btn">Voir plus</a>
      </div>
      <div class="project">
        <h3 class="project-title">Communication digitale</h3>
        <img src="/Users/oscarperrault/Library/Mobile Documents/com~apple~CloudDocs/Documents/Portfolio B3 Webdesign/marketing-medias-sociaux-marketing-numerique-icones-3d-megaphone-ordinateur-portable-fond-couleur-bleue.png" alt="Image Projet 2">
        <a href="#" class="btn">Voir plus</a>
      </div>
    </div>
    <div class="big-project">
        <h3 class="project-title">Webdesign</h3>
        <img src="/Users/oscarperrault/Library/Mobile Documents/com~apple~CloudDocs/Documents/Portfolio B3 Webdesign/webdesign.png" alt="Image Projet 3">
        <a href="#" class="btn">Voir plus</a>
    </div>
  </div>
</section>

</template>

<style scoped>
#projets {
  text-align: center;
}
.section-title{
    margin-bottom: 20px;
}
.projects-container{
    display: flex;
  justify-content: space-between;
}

.project {
  width: calc(50% - 10px); 
  text-align: center; 
  padding: 20px; 
  border: 1px solid #ddd; 
  border-radius: 5px; 
}

.project-title{
    margin-bottom: 20px;
}

.big-project {
  width: calc(100% - 2px); 
  margin-top: 20px;
  padding: 20px; 
  border: 1px solid #ddd; 
  border-radius: 5px; 
}

.project img {
  max-width: 100%; 
  height: 400px; 
  margin-bottom: 20px; 
}
.big-project img{
    max-width:100%;
    height: 700px; 
    margin-bottom: 20px; 
}

.btn {
  background-color: #E65D5D; 
  color: #fff; 
  border: none; 
  padding: 10px 20px; 
  border-radius: 5px; 
}

</style>