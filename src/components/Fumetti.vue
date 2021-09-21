<template>
  <div class="container">
        <div class="nero">
            <Prop_copertina
                v-for="(copertina, index) in copertine"
                :key="index"
                :promp="copertina"
            />
        </div>
     <div class="con-but"><button>cliccami</button> </div>
  </div>
</template>

<script>
import copertine from '../data/dc-comics.json';
import Prop_copertina from '@/components/Prop_copertina.vue'

export default {
    name:'Fumetti',
    components:{
        Prop_copertina

    },
    data(){
        return{
            copertine: copertine
        }
    }
}
</script>

<style scoped lang="scss">
.container{
    display: flex;
    flex-direction: column;
    justify-content: space-around;
    align-items: center;
    padding: 10px;
    background-color: black;
    width: 100%;
    min-height: 450px;

}
.nero{
    
    display: flex;
    width: 90%;
    min-height: 350px;
    margin: 0 auto;
    flex-wrap: wrap;
   
    justify-content: space-between;
    
    

}
button {
    text-align: center;
  background-color: blue;
  border: none;
  color: white;
  padding: 15px 32px;
  text-align: center;
  text-decoration: none;
  display: inline-block;
  font-size: 16px;
}
.con-but{
    width: 50px;
}
</style>