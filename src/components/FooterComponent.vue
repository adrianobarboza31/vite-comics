<template>
<footer>
    <div class="div1 ">
        <div class="container flex1">
            <div class="box">
            SIGN-UP NOW!
        </div>
            <div class="flex2">
                <div>
                   <h3>FOLLOW US</h3>
                </div>
                <div>
                    <img src="../assets/img/footer-facebook.png" alt="">
                </div>
                <div>
                    <img src="../assets/img/footer-twitter.png" alt="">
                </div>
                <div>
                    <img src="../assets/img/footer-youtube.png" alt="">
                </div>
                <div>
                    <img src="../assets/img/footer-pinterest.png" alt="">
                </div>
                <div>
                    <img src="../assets/img/footer-periscope.png" alt="">
                </div>
            </div>

        </div>
        
    </div>
    <div class="div2">

    </div>
</footer>
</template>

<script>
    export default {
        
    }
</script>

<style lang="scss" scoped>
@use '../assets/styles/partials/variables' as *;

.div2{
   height: 40px;
   background:$nero; 
}
.div1{
    height: 86px;
    background: $grigio;
    color: white;
}
.box{
border: 2px solid $blu;
width: 150px;
text-align: center;
padding: 10px;
}
.flex1{
    display: flex;
    justify-content: space-between;
}
.flex2{
    display: flex;
    align-items: center;
}
.flex2 div{
    padding: 0 10px;
}
h3{
    color: $blu;
}
</style>