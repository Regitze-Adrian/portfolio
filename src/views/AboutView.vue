<template>
  <div class="about">
    <h1>ABOUT ME</h1>
  </div>

  <div><div> 1 </div>
    <AboutMeComponent />
  </div>

</template>

<style lang="scss"> // det her rammer alle components
    body {
      background-color: rgb(179, 211, 234);
    }

    .about {
      color: rgb(0, 0, 0);
      font-family: 'Work Sans', sans-serif;
    }

    .aboutmebox {
        background-color: rgb(241, 217, 217);
        width: 500px;
        height: 400px;
        display: flex;
        // justify-content: center;
        // align-items: center;
        padding: 20px;
        display: inline-flex;
        text-align: left;
    }

   


</style>

<script>
import AboutMeComponent from '../components/AboutMeComponent.vue' 

export default {
    components: {
        AboutMeComponent
    }
}
</script>