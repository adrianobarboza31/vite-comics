<template>
    <section>
        <div class="container">
        <h2> {{message}} </h2>
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
   background: $grigioscuro;
   color: white;
   height: 130px;
}
div.container{
    display: flex;
    align-items: center;
    height: 130px;
}
</style>