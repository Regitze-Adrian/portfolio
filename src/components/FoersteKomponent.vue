<template>
 <div class="container-md">
  <div class="row">
  <div class="col-12 col-sm-12 col-md-12 mb-12"><div class="projecttitle">
   <span style="--i:1">P</span>
   <span style="--i:2">R</span>
   <span style="--i:3">O</span>
   <span style="--i:4">J</span>
   <span style="--i:5">E</span>
   <span style="--i:6">K</span>
   <span style="--i:7">T</span>
   <span style="--i:8">E</span>
   <span style="--i:9">R</span>
  </div></div></div></div>
 
 <div class="container-md"> <!-- switch to margin x over MD size(fluid and !fluid) -->
  <div class="row">
  <div class="col-12 col-sm-6 col-md-4 mb-4">
  <div class="card" style="width: 18rem;">
  <img src="../assets/halloweencrop.png" class="card-img-top" alt="halloweenposter">
  <div class="card-body">
    <h5 class="card-title">Halloween Plakat</h5>
    <p class="card-text">Plakat lavet som reklame for en Halloween-fest. Denne plakat er lavet i Adobe Illustrator ved selv at tegne alle elementerne med vektorgrafik.</p>

  </div>
  </div>
</div>
<div class="col-12 col-sm-6 col-md-4 mb-4">
  <div class="card" style="width: 18rem;">
  <img src="../assets/beatupcrop.png" class="card-img-top" alt="beat up">
  <div class="card-body">
    <h5 class="card-title">Beat Up Face</h5>
    <p class="card-text">Photoshop øvelse ved at redigere ansigtet, så det ligner, at det er blevet smadret ved at bruge diverse værktøjer og blende andre elementer ind.</p>

  </div>
</div>
</div>
<div class="col-12 col-sm-6 col-md-4 mb-4">
  <div class="card" style="width: 18rem;">
  <img src="../assets/trapholtcrop.png" class="card-img-top" alt="trapholt">
  <div class="card-body">
    <h5 class="card-title">Trapholt</h5>
    <p class="card-text"> Fiktivt semesterprojekt om at finde nyt koncept til Trapholt: Dating. I dette projekt har vi indsamlet data, fremstillet kreative produkter og kodet en hjemmeside.</p>

  </div>
  </div>
</div>
<div class="col-12 col-sm-6 col-md-4 mb-4">
  <div class="card" style="width: 18rem;">
  <img src="../assets/rjlogocrop.png" class="card-img-top" alt="rj logo">
  <div class="card-body">
    <h5 class="card-title">Remote Job Portal</h5>
    <p class="card-text"> Fiktivt projekt i UX om at kreere en ny jobportal. Vi skabte en brugervenlig jobportal ved hjælp af dataindsamling og lavede designet i Adobe XD. </p>

  </div>
</div>
</div>
<div class="col-12 col-sm-6 col-md-4 mb-4">
  <div class="card" style="width: 18rem;">
  <img src="../assets/citybranding.png" class="card-img-top" alt="city branding">
  <div class="card-body">
    <h5 class="card-title">City Branding</h5>
    <p class="card-text">Projekt om at brande Esbjerg på en ny måde. Vi valgte at give Festugen et twist ved at tilføje et ColorRun. Vi fremstillede infographics, videoer og en plakat. </p>

  </div>
</div>
</div>

<div class="col-12 col-sm-6 col-md-4 mb-4">
  <div class="card" style="width: 18rem;">
  <img src="../assets/techhubcrop.png" class="card-img-top" alt="techhub">
  <div class="card-body">
    <h5 class="card-title">TechHub</h5>
    <p class="card-text">Semesterprojekt om at skabe en ny visuel identitet for firmaet TechHub Syd samt TechHub Invest. Inkluderer bl.a. en hjemmeside kodet i Vue3 samt roll-up banner. </p>

  </div>
</div>
</div>

<div class="col-12 col-sm-6 col-md-4 mb-4">
  <div class="card" style="width: 18rem;">
  <img src="../assets/eb.png" class="card-img-top" alt="esbjerg bryghus">
  <div class="card-body">
    <h5 class="card-title">Esbjerg Bryghus</h5>
    <p class="card-text">Opgave om at skabe merchandise for Esbjerg Bryghus. Jeg valgte at lave den ikoniske sømand til en stamkunde, der får en øl, som tryk på en trøje.</p>

  </div>
</div>
</div>

<div class="col-12 col-sm-6 col-md-4 mb-4">
  <div class="card" style="width: 18rem;">
  <img src="../assets/emag.png" class="card-img-top" alt="e-magasin">
  <div class="card-body">
    <h5 class="card-title">E-magasin</h5>
    <p class="card-text">Opgave om at skabe et e-magasin for Espresso Houses årsrapport. Indeholder interaktive elementer såsom knapper og animationer. Lavet i InDesign.</p>

  </div>
</div>
</div>

<div class="col-12 col-sm-6 col-md-4 mb-4">
  <div class="card" style="width: 18rem;">
  <img src="../assets/webshop.png" class="card-img-top" alt="webshop">
  <div class="card-body">
    <h5 class="card-title">Hjemmeside</h5>
    <p class="card-text">Hjemmeside kodet i Vue3 og JavaScript. Display hjemmeside for webshop med dynamisk data sat op på Firebase. Produkter kan rettes direkte på hjemmesiden.</p>

  </div>
</div>
</div>
  </div>
  
</div>
</template>

<style>
 .projecttitle {
    font-family: 'Work Sans', sans-serif;
    font-size: 38px;
    color: rgb(0, 0, 0);
    margin-top: 20px;
    margin-bottom: 50px;
    position: relative;
  }

.projecttitle span {
  position: relative;
  display: inline-block;
  font-size: 40px;
  color: rgb(0, 0, 0);
  text-transform: uppercase;
  animation: flip 2s;
  animation-delay: calc(.2s * var(--i))
}
@keyframes flip {
  0%,80% {
    transform: rotateY(360deg) 
  }
}

.container-md {
  display:flex;

}

.card {
        margin: 0 auto; 
        float: none; 
        margin-bottom: 10px;
        text-align: left;
}

</style>