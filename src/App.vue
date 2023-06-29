<script>
import AppHeader from './components/AppHeader.vue'

export default {
  data() {
    return {
      classe: 100
    }
  },
  components: {
    AppHeader
  }
}
n
</script>

<template>
  <!-- header-->
  <AppHeader />


  <!-- main-->
  <AppMain />
</template>


<style>
h3 {
  color: rgb(231, 65, 23)
}
</style>