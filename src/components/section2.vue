<template>
<section>
<div class="container   flex2 ">
    <div class="flex">
        <img src="../assets/img/buy-comics-digital-comics.png" alt="">
        <div>
            digital comics
        </div>
    </div>
    <div class="flex">
        <img src="../assets/img/buy-comics-merchandise.png" alt="">
        <div>
            dc merchandise
        </div>
    </div>
    <div class="flex">
        <img src="../assets/img/buy-comics-subscriptions.png" alt="">
        <div>
            subscription
        </div>
    </div>
    <div class="flex">
        <img src="../assets/img/buy-comics-shop-locator.png" alt="">
        <div>
            comic shop locator
        </div>
    </div>
    <div class="flex">
       <img src="../assets/img/buy-dc-power-visa.svg" alt="">
        <div>
            dc power visa
        </div>
    </div>
</div>
</section>
</template>

<script>
    export default {
        data(){
            return{
               
            }
        }
    }
</script>

<style lang="scss" scoped>
@use '../assets/styles/partials/variables' as *;
section{
    background: $blu;
    color: white;
  
}
.flex{
    display: flex;
    align-items: center;
}
.flex2{
    display: flex;
  justify-content: space-around;
  height: 150px;
}
img{
    width: 50px;
    height: 60px;
    object-fit: contain;
}
.spacearound{
    justify-content: space-between;
}
div.flex img,div{
    padding:0 5px;
}
</style>