<template>
  <div class="home">
    <div class="logo">
    <img alt="Vue logo" src="../assets/logo.png">
  </div>
</div>
  <div class="nametitle"> Regitze Adrians </div>
  <div class="portfoliotitle">
   <span style="--i:1">P</span>
   <span style="--i:2">O</span>
   <span style="--i:3">R</span>
   <span style="--i:4">T</span>
   <span style="--i:5">F</span>
   <span style="--i:6">O</span>
   <span style="--i:7">L</span>
   <span style="--i:8">I</span>
   <span style="--i:9">O</span>
  </div>
  
<div class="containertitle"> JEG HAR KOMPETENCER INDENFOR... </div>

<div class="container-md justify-content-center">
  <div class="row">
  <div class="col-12 col-sm-6 col-md-4 mb-4 d-flex justify-content-center">
  <div class="cardone">
    <div class="cardbubble"> UX <br> UI </div>
  </div></div>
 

  
  <div class="col-12 col-sm-6 col-md-4 mb-4 d-flex justify-content-center">
  <div class="cardtwo">
    <div class="cardbubble"> DESIGN </div>
</div></div>


  
  <div class="col-12 col-sm-6 col-md-4 mb-4 d-flex justify-content-center">
  <div class="cardthree">
    <div class="cardbubble"> FRONT <br> END <br> DEV. </div>
</div></div>



  
  <div class="col-12 col-sm-6 col-md-4 mb-4 d-flex justify-content-center">
  <div class="cardfour">
    <div class="cardbubble"> SOCIAL <br> MEDIA </div>
</div></div>
  


   
  <div class="col-12 col-sm-6 col-md-4 mb-4 d-flex justify-content-center">
  <div class="cardfive">
    <div class="cardbubble"> VIDEO </div>
</div></div>
  </div>
 </div>



</template>

<style lang="scss">
  
  .home {
  margin-top: 30px;
  }

  body {
      background-color: rgb(255, 248, 235);
    }

  .nametitle {
    font-family: 'Cookie', cursive;
    font-size: 72px;
    color: rgb(255, 68, 0);
  }

  .portfoliotitle {
    font-family: 'Work Sans', sans-serif;
    font-size: 38px;
    color: rgb(0, 0, 0);
    margin-top: -40px;
    margin-left: 70px;
    margin-bottom: 50px;
    position: relative;
  }

.portfoliotitle span {
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

  .containertitle {
    color: black;
    font-size: 28px;
    font-family: 'Work Sans', sans-serif;

  }

.container-md {
  display: flex;
  align-items: center;
  justify-content: center;
  gap: 40px;
  margin-top: 10px;
  }

.cardone {
  width: 220px;
  height:325px; 
  border-radius: 15px;
  display: flex;
  justify-content: center;
  align-items: center;
  background-image: linear-gradient(to bottom right, red, yellow);
  box-shadow: 5px 10px 10px 3px rgb(128, 42, 6);
  font-family: 'Oswald', sans-serif;
  font-size: 28px;
  color: black;
}

.cardtwo {
  width: 220px;
  height:325px; 
  border-radius: 15px;
  display: flex;
  justify-content: center;
  align-items: center;
  background-image: linear-gradient(to bottom right, yellow, green);
  box-shadow: 5px 10px 10px 3px rgb(5, 85, 32);
  font-family: 'Oswald', sans-serif;
  font-size: 28px;
  color: black;
}

.cardthree {
  width: 220px;
  height:325px; 
  border-radius: 15px;
  display: flex;
  justify-content: center;
  align-items: center;
  background-image: linear-gradient(to bottom right, green, rgb(58, 193, 237));
  box-shadow: 5px 10px 10px 3px rgb(6, 89, 92);
  font-family: 'Oswald', sans-serif;
  font-size: 28px;
  color: black;
}

.cardfour {
  width: 220px;
  height:325px; 
  border-radius: 15px;
  display: flex;
  justify-content: center;
  align-items: center;
  background-image: linear-gradient(to bottom right, rgb(58, 193, 237), blue);
  box-shadow: 5px 10px 10px 3px rgb(10, 39, 112);
  font-family: 'Oswald', sans-serif;
  font-size: 28px;
  color: black;
}

.cardfive {
  width: 220px;
  height:325px; 
  border-radius: 15px;
  display: flex;
  justify-content: center;
  align-items: center;
  background-image: linear-gradient(to bottom right, blue, purple);
  box-shadow: 5px 10px 10px 3px rgb(63, 8, 95);
  font-family: 'Oswald', sans-serif;
  font-size: 28px;
  color: black;
}

.cardbubble {
  width: 150px;
  height: 150px; 
  border-radius: 100px;
  background-color: white;
  display: flex;
  justify-content: center;
  align-items: center;
  line-height: 24pt;
}

</style>

<script>
// @ is an alias to /src

export default {
  name: 'HomeView',
  components: {
    
  }
}
</script>
