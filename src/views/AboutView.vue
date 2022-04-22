<template>
   <div class="container-md">
        <div class="row">
          <div class="col-12 col-sm-6 col-md-4 mb-4">
            <div class="ommigtitle">
   <span style="--i:1">A</span>
   <span style="--i:2">B</span>
   <span style="--i:3">O</span>
   <span style="--i:4">U</span>
   <span style="--i:5">T</span>
  </div>
    </div>
      </div>
        </div>

   

    <div class="container-md">
        <div class="row">
          <div class="col-12 col-sm-6 col-md-6 mb-4">
            <div class="aboutme">
    Jeg hedder Regitze Adrian, og jeg er 22 år. Jeg studerer til multimediedesigner på Erhvervsakademiet Sydvest i Esbjerg, hvor jeg har tillært mig en masse viden indenfor grafisk design, front-end programmering, UX og UI. <br> <br>
    Det er mine store interesser inden for design og IT, som har medvirket til mit valg af dette studie. Jeg har altid holdt af at tegne, at være kreativ og at spille computerspil, så ved at vælge dette felt, er mine passioner blevet sammensmeltet. <br> <br>
    Jeg mestrer flydende dansk og engelsk i både skrift og tale, jeg er komfortabel med tysk, og jeg er i gang med at lære græsk.
  </div>
  </div>
  <div class="col-12 col-sm-6 col-md-6 mb-4">
  <div class="youtubebox">
    <section>
      <iframe width="560" height="315" src="https://www.youtube.com/embed/c6NJNOi3Rms" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
    </section>
  </div>
</div>
 </div>
 </div>

<div class="container-md">
  <div class="row">
 <div class="col-12 col-sm-12 col-md-12 mb-12">
  <div class="bjaelke">
   GRADUERET MULTIMEDIEDESIGNER I 2023
  </div>
  </div>
  </div>


</div>


</template>

<style lang="scss"> // det her rammer alle components
   

    .ommigtitle {
      color: rgb(0, 0, 0);
      font-family: 'Work Sans', sans-serif;
      position: relative;
      margin-bottom: 50px;
      display: flex;
    }

    .ommigtitle span {
      position: relative;
      display: inline-block;
      font-size: 40px;
      color: rgb(0, 0, 0);
      text-transform: uppercase;
      animation: flip 2s;
      animation-delay: calc(.2s * var(--i))
}


  .container-md {
  display: flex;
  align-items: center;
  justify-content: center;
  width:1200px;
  }

.aboutme {
  color:black;
  text-align: left;
}

.bjaelke {
  width: 1165px;
  height:105px; 
  border-radius: 5px;
  display: flex;
  justify-content: center;
  align-items: center;
  background-image: linear-gradient(to bottom right, rgb(0, 255, 136), rgb(0, 179, 255));
  box-shadow: 5px 10px 10px 3px grey;
  font-family: 'Oswald', sans-serif;
  font-size: 28px;
  color: black;
}


</style>

<script>


export default {
    components: {

    }
}
</script>