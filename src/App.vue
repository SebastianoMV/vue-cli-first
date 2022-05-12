<template>
  <div id="app">
   <TitleComp />
   <HeroComp />
  </div>
</template>

<script>
import TitleComp from './components/Title.vue'
import HeroComp from './components/Hero.vue'

export default {
  name: 'App',
  components: {
    TitleComp,
    HeroComp
  }
}
</script>

<style>


</style>
