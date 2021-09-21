<template>
    <div class="container3">
      <img class="resize" :src="promp.thumb" alt="">
      <div class="serie">{{promp.series}}</div>
      
    </div>
</template>

<script>
export default {
    name:'Prop_copertina',
    props: ['promp']
}
</script>

<style scoped lang="scss">
    .container3{
        display: flex;
        flex-direction: column;
        justify-content: space-around;
        align-items: center;
        width: 15%;
        flex-wrap: wrap;

}
    .resize{
        width: 130px;
        height: 130px;
        object-fit: cover;
         object-position:  -20% -0.01%;
    }
    .serie{
        text-align: center;
        color: white;
        height: 30px;
    }
</style>