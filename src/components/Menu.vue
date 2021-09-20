<template>
  <div >
    <div class="container">
        <img src="..\assets\vue-dc-comics-1\img\dc-logo.png" alt="">
        <ul>
            <li><a href="#"> Prova</a></li>
            <li><a href="#"> Prova</a></li>
            <li><a href="#"> Prova</a></li>
            <li><a href="#"> Prova</a></li>
            <li><a href="#"> Prova</a></li>
            <li><a href="#"> Prova</a></li>
            <li><a href="#"> Prova</a></li>
            <li><a href="#"> Prova</a></li>
            <li><a href="#"> Prova</a></li>
            <li><a href="#"> Prova</a></li>
          
        </ul>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Menu',

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

    }
</style>