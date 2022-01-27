<template>
  <div id="app">
    <header-box />
    <jumbotron-box />
    <market-box />
  </div>
</template>

<script>
import MarketBox from './components/MarketBox.vue'
import HeaderBox from './components/HeaderBox.vue'
import JumbotronBox from './components/JumbotronBox.vue'


export default {
  name: 'App',
  components: {
    HeaderBox,
    JumbotronBox,
    MarketBox
    
  }
}
</script>

<style lang="scss">
  @import './style/main.scss'
</style>
