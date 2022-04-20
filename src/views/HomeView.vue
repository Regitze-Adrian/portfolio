<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
  </div>

  <div class="nametitle"> Regitze Adrians </div>
  <div class="portfoliotitle"> PORTFOLIO </div>

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
