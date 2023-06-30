<script>
import AppHeader from './components/AppHeader.vue'
import AppHero from './components/AppHero.vue'
import AppMain from './components/AppMain.vue'
import ComicCard from './components/ComicCard.vue'
export default {
  data() {
    return {
      classe: 100
    }
  },
  components: {
    AppHeader, AppHero, AppMain, ComicCard
  }
}

</script>

<template>
  <!-- header-->
  <AppHeader />
  <AppHero />
  <ComicCard />
  <!-- main-->
  <AppMain />
</template>


<style>
h3 {
  color: rgb(231, 65, 23)
}
</style>