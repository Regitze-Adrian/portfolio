<template>
  <NavigationComponent />
  <router-view/>
  <FooterComponent />
</template>

<script>
import NavigationComponent from './components/NavigationComponent.vue'
import FooterComponent from './components/FooterComponent.vue'

export default {
  setup () {},
  components: {
    FooterComponent,
    NavigationComponent,
    }
}
</script>


<style lang="scss">

@import url('https://fonts.googleapis.com/css2?family=Cookie&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Work+Sans&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Domine:wght@600&family=Oswald&display=swap');

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #50392c;
}

nav {
  padding: 30px;

  a {
    font-weight: bold;
    color: #75451e;
    font-family: 'Work Sans', sans-serif;
    font-size: 16px;
    letter-spacing: 1px;

    &.router-link-exact-active {
      color: #f54323;
    }
  }
}
</style>
