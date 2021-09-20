<template>
  <div id="app">
    <Menu/>
   <Main/>
   <Footer/>
  </div>
</template>

<script>
import Menu from './components/Menu.vue'
import Main from './components/Main.vue'
import Footer from './components/Footer.vue'

export default {
  name: 'App',
  components: {
    Menu,
    Main,
    Footer
  }
}
</script>

<style lang="scss">
@import "./style/general.scss" 
 
</style>
