<template>
   <HeaderComponent />
   <main>
    <section1 />
    <sectionSeries/>
    <section2 />
    <section3 />
   </main>
   <FooterComponent />
</template>

<script>
import HeaderComponent from'./components/HeaderComponent.vue';
import FooterComponent from './components/FooterComponent.vue';
import section1 from './components/section1.vue';
import section2 from './components/section2.vue';
import section3 from './components/section3.vue';
import sectionSeries from './components/sectionSeries.vue';
    export default {
        components:{
            HeaderComponent,
            FooterComponent,
            section1,
            section2,
            section3,
            sectionSeries,
        }
    }
</script>

<style lang="scss" scoped>

</style>