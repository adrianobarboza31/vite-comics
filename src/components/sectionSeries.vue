<template>
   <section>
    <div class="container">
        <div>
            <span class="bg-bl">current series</span>
        </div>
        <div class="dflex">
            <div class="card" v-for="(value,index) in card">
            <div>
                <img :src="value.thumb" alt="">
                
            </div>
            <div class="giu">
                <span>{{value.series}}</span>
            </div>
        </div>
        </div>
        <div class="centro">
            
                <span class="bg-blu">load more</span>
            
        </div>
    </div>
   </section>
</template>

<script>
import{series} from '../dc-comics'
    export default {
        data(){
            return{
                card:series,
            }
        }
    }
</script>

<style lang="scss" scoped>
@use '../assets/styles/partials/variables' as *;
section{
  
    background: $grigioscuro;
}
.dflex{
    display: flex;
    flex-wrap: wrap;
}
.card{
    width: calc((100% - 60px )/ 6);
    padding: 20px 5px;
}
img{
    width: 100%;
    height: 200px;
    
}
span{
    color: white;
    text-transform: uppercase;
}
.bg-blu{
    background: $blu;
    width: 100px;
    padding: 5px 40px;
}
.centro{
    text-align: center;
    padding-top: 20px;
    padding-bottom: 10px;
}
.bg-bl{
    font-size: 30px;
    background-color: $blu;
    padding: 5px 10px;
}
.giu{
    padding-top: 10px;
}
</style>