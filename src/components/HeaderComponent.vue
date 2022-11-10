<template>
    <header>
        <div class="bgg-black">
    </div>
    <nav class="container">
        <img src="../assets/img/dc-logo.png" alt="">
        <ul>
            <li class="blu" v-for ="(value,index) in link">{{value.menu}}</li>
        </ul>
    </nav>
    </header>
   
</template>

<script>
    export default {
        data(){
          return{
            link:[
                {
                    menu:"characters",
                    active:false
                },
                {
                    menu:"comics",
                    active:true
                },
                {
                    menu:"movies",
                    active:false
                },
                {
                    menu:"tv",
                    active:false
                },
                {
                    menu:"games",
                    active:false
                },
                {
                    menu:"collectibels",
                    active:false
                },
                {
                    menu:"videos",
                    active:false
                },
                {
                    menu:"fans",
                    active:false
                },
                {
                    menu:"news",
                    active:false
                },
                {
                    menu:"shop",
                    active:false
                },
            ]
          }  
        }
    }
</script>

<style lang="scss" scoped>
@use '../assets/styles/partials/mixins' as*;
@use '../assets/styles/partials/variables' as*;
.bgg-black{
    background-color: black;
    height: 40px;
    width: 100%;
}
li{
    list-style: none;
   padding: 15px;
}
nav{
    @include dflex;
}
ul{
    @include  dflexulnav;
}
.blu:hover{
    color: $blu;
}
li::after{
    content: "";
    display: none;
    width: 100%;
    height: 3px;
    background:$blu;
    
}
.blu:hover::after {
    display: block;
}
</style>