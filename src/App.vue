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
    NavigationComponent
    }
}
</script>


<style lang="scss">
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
    color: #503c2c;

    &.router-link-exact-active {
      color: #009dff;
    }
  }
}
</style>
