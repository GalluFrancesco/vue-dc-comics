<template>
  <div id="app">
    <header-box />
    <jumbotron-box />
  </div>
</template>

<script>
import HeaderBox from './components/HeaderBox.vue'
import JumbotronBox from './components/JumbotronBox.vue'


export default {
  name: 'App',
  components: {
    HeaderBox,
    JumbotronBox
    
  }
}
</script>

<style lang="scss">
  @import './style/main.scss'
</style>
