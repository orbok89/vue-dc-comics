<template>
  <div id="app">
    <Menu/>
    <Jumbo/>
   <Main/>
   <Footer/>
  </div>
</template>

<script>
import Menu from './components/Menu.vue'
import Main from './components/Main.vue'
import Footer from './components/Footer.vue'
import Jumbo from './components/Jumbo.vue'

export default {
  name: 'App',
  components: {
    Menu,
    Main,
    Footer,
    Jumbo
  }
}
</script>

<style lang="scss">
@import "./style/general.scss" 
 
</style>
