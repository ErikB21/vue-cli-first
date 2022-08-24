<template>
  <div id="app">
    <HeroComponent/>
  </div>
</template>

<script>
import HeroComponent from './components/HeroComponent.vue';
export default {
  name: 'App',
  components: {
    HeroComponent
}
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  text-align: center;
}
</style>
