<script>
import AppHeader from './components/AppHeader.vue'
import AppHero from './components/AppHero.vue'
export default {
  data() {
    return {
      classe: 100
    }
  },
  components: {
    AppHeader, AppHero
  }
}

</script>

<template>
  <!-- header-->
  <AppHeader />
  <AppHero />

  <!-- main-->
  <AppMain />
</template>


<style>
h3 {
  color: rgb(231, 65, 23)
}
</style>