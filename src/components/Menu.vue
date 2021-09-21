<template>
  <div >
    <div class="container">
        <img src="..\assets\vue-dc-comics-1\img\dc-logo.png" alt="">
        <ul>
            <li v-for="(link,index) in links" :key="index"><a href="#"> {{link.text}}</a></li>
          
          
        </ul>
    </div>
  </div>
</template>

<script>
import * as links from '../data/data.js';
export default {
  name: 'Menu',
  data() {
    return {
      links: links.headerLinks
    }
  }

}
</script>

<style scoped lang="scss">
    .container{
        display: flex;
        justify-content: space-around;
        align-items: center ;
        height: 150px;
    }
     ul{
         width: 50%;
        display: flex;
        justify-content: space-between;
           list-style-type: none;
        li :hover{
            color: red;
            border-bottom: 2px solid blue;
        }
      }
      a{
        text-decoration: none;
      }
</style>