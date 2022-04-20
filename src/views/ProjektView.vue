<template>
    <div>
        <div> Projekter </div>
        <FoersteKomponent />
    </div>

<div class="box1"></div> <!-- slet -->

</template>

<style lang="scss"> // det her rammer alle components
    
    body {
      background-color: rgb(226, 244, 164);
    }
    
    .box1 {
        background-color: purple;
        width:40px;
        height: 40px;
    }
</style>

<script>
import FoersteKomponent from '../components/FoersteKomponent.vue' 

export default {
    components: {
        FoersteKomponent
    }
}
</script>