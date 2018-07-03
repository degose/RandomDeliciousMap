<template>
  <div id="app">
    <app-map></app-map>
  </div>
</template>

<script>
import AppMap from "./components/map";

export default {
  name: 'app',
  components: {
      AppMap
  },
  data () {
    return {
    }
  }
}
</script>

<style lang="scss">
  #app {
    color: #56b983;
  }
</style>