<template>
  <div id="app">
    <myTitle></myTitle>
    <newHero></newHero>
  </div>
</template>

<script>
import myTitle from './components/myTitle.vue'
import newHero from './components/newHero.vue'

export default {
  name: 'App',
  components: {
    myTitle,
    newHero
  }
}
</script>

<style>

</style>
