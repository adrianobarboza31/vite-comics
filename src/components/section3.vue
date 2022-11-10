<template>
 <section class="">
    <div class="relative container flex2">
        <div class="flex">
            <ul>
                <li>
                    <h3>
                        DC COMICS
                    </h3>
                </li>
                <li>
                    characters
                </li>
                <li>
                    comics
                </li>
                <li>
                    movies
                </li>
                <li>
                    tv
                </li>
                <li>
                    games
                </li>
                <li>
                    videos
                </li>
                <li>
                    news
                </li>
                <ul>
                <li>
                    <h3>
                        shops
                    </h3>
                </li>
                <li>
                    characters
                </li>
                <li>
                    comics
                </li>
               
               
            </ul>
            </ul>
            <ul>
                <li>
                    <h3>
                        DC
                    </h3>
                </li>
                <li>
                    Terms Of Use
                </li>
                <li>
                    Privacy policy(new)
                </li>
                <li>
                    Ad Choises
                </li>
                <li>
                    advertsing
                </li>
                <li>
                    jobs
                </li>
                <li>
                    subscriptions
                </li>
                <li>
                    talent Workshops
                </li>
                <li>
                    talent Workshops
                </li>
                <li>
                    talent Workshops
                </li>
                <li>
                    talent Workshops
                </li>
                <li>
                    talent Workshops
                </li>
            </ul>
            <ul>
                <li>
                    <h3>
                        sites
                    </h3>
                </li>
                <li>
                    characters
                </li>
                <li>
                    comics
                </li>
                <li>
                    movies
                </li>
                <li>
                    tv
                </li>
                <li>
                    games
                </li>
               
            </ul>
           
        </div>
        <div class="ass">
            <img src="../assets/img/dc-logo-bg.png" alt="">
        </div>
    </div>
 </section>
</template>

<script>
    export default {
        
    }
</script>

<style lang="scss" scoped>
section{
    height: 380px;
    background-image:url("../assets/img/footer-bg.jpg");
    background-size: cover;
}
li{
    color: gray;
    list-style: none;
}
.flex{
    display: flex;
    width: 400px;
    
    justify-content: space-between;
}
h3{
    color: white;
    padding-bottom: 10px;
    padding-top: 15px;
    text-transform: uppercase;
}
.flex2{
    display: flex;
    justify-content: space-between;
}
// .relative{
//     position: relative;
// }
// .ass{
//     position: absolute;
//     right: 0;
//     top: 0;
    
// }
.ass img{
    width: 400px
    ;
    z-index: -1;
}
</style>