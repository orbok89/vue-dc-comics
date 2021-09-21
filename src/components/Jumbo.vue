<template>
  <div >
    <div class="container">
        <img src="..\assets\vue-dc-comics-1\img\jumbotron.jpg" alt="">
    </div>
  </div>
</template>

<script>
export default {
  name: 'Jumbo',

}
</script>
<style scoped lang="scss">
.container{
    width: 100%;
    height: 350px;
    background-color: aqua;
}
img{
    object-fit:cover;
    width:100%;
    height:100%;
    
    object-position:  -20% -0.01%;
}
</style>