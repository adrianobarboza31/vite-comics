<template>
    <section>
        <div class="container">
       
    </div>
    </section>
    
</template>

<script>
    export default {
        data(){
            return{
                message:"--> Content goes here <--"
            }
        }
        
    }
</script>
<style lang="scss" scoped>
@use '../assets/styles/partials/variables' as *;
section{
   background-image: url("../assets/img/jumbotron.jpg");
   color: white;
   height: 400px;
   background-size: cover;
}
div.container{
    display: flex;
    align-items: center;
    height: 130px;
}
</style>