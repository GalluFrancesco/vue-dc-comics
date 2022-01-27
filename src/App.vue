<template>
  <div id="app">
    <header-box />
    <jumbotron-box />
    <market-box />
    <footer-box />
    <social-box />
  </div>
</template>

<script>
import MarketBox from './components/MarketBox.vue'
import HeaderBox from './components/HeaderBox.vue'
import JumbotronBox from './components/JumbotronBox.vue'
import FooterBox from './components/FooterBox.vue'
import SocialBox from './components/SocialBox.vue'


export default {
  name: 'App',
  components: {
    HeaderBox,
    JumbotronBox,
    MarketBox,
    FooterBox,
    SocialBox
    
  }
}
</script>

<style lang="scss">
  @import './style/main.scss'
</style>
