<template>
  <div >
    <div class="container">
      
        <div class="blu">
            <div>
                <img class="resize"  src="..\assets\vue-dc-comics-1\img\buy-comics-digital-comics.png" alt="">
                <div>digital comics</div>
            </div>
            <div>
                <img class="resize"  src="..\assets\vue-dc-comics-1\img\buy-comics-digital-comics.png" alt="">
                <div>dc merchandise</div>
            </div>
            <div>
                <img class="resize"  src="..\assets\vue-dc-comics-1\img\buy-comics-digital-comics.png" alt="">
                <div>subscription</div>
            </div>
            <div>
                <img class="resize"  src="..\assets\vue-dc-comics-1\img\buy-comics-digital-comics.png" alt="">
                <div>comic shop locator</div>
            </div>
            <div>
                <img class="resize"  src="..\assets\vue-dc-comics-1\img\buy-comics-digital-comics.png" alt="">
                <div>dc power visa</div>
            </div>
        </div>

    </div>
  </div>
</template>

<script scoped lang="scss">
export default {
  name: 'Main',

}
</script>
<style scoped lang="scss">
.container{
    width: 100%;
    height: 150;
   
}
.nero{
    display: flex;
    width: 90%;
    height: 150px;
    margin: 0 auto;
    color: white;
    align-items: center;

}
.blu{
    display: flex;
    width: 100%;
    height: 150px;
    background-color: blue;
    justify-content: space-around;
    align-items: center;
}
.resize{
     
}
   
</style>