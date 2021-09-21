<template>
  <div id="app">
    <Menu/>
    <Jumbo/>
    <Fumetti/>
    <Main/>
    <Footer/>
  </div>
</template>

<script>
import Menu from './components/Menu.vue'
import Main from './components/Main.vue'
import Footer from './components/Footer.vue'
import Jumbo from './components/Jumbo.vue'
import Fumetti from './components/Fumetti.vue'

export default {
  name: 'App',
  components: {
    Menu,
    Main,
    Footer,
    Jumbo,
    Fumetti
  }
}
</script>

<style lang="scss">
@import "./style/general.scss" 
 
</style>
