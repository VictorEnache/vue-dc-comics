<template>
    <header id="SiteHeader">
        <div class="container">
            <div class="logo">
                <img src="../assets/img/dc-logo.png" alt="">
            </div>
            <nav>
                <ul>
                    <li :key='link' v-for='link in navigation' :class='link === "COMICS" ? "active" : ""'>{{link}}</li>
                </ul>
            </nav>
        </div>
    </header>
</template>

<script>


export default {
    name: 'SiteHeader',

    data() {
        return{
            navigation:[
                'CHARACTERS',
                'COMICS',
                'MOVIES',
                'TV',
                'GAMES',
                'COLLECTIBLES',
                'VIDEOS',
                'FANS',
                'NEWS',
                'SHOP'
            ]
        }
    }
}
</script>

<style lang="scss">
 #SiteHeader{

     .container{
         margin: auto;
         width: 1080px;
         display: flex;
         justify-content: space-between;
         align-items: center;

         .logo{
             height:80px;
             width: 80px;

             img{
                 width: 100%;
                 object-fit: cover;
                 display: block;
             }
         }

         nav{
                         

             ul{
                 
                 list-style: none;
                 display: flex;
                 column-gap: 35px;
                 font-size: 11px;

                 li{
                     padding: 50px 0;
                 }

                 .active{
                    color: blue;
                    border-bottom: 4px solid blue;
                 }
                 
             }
         }
     }
 }
</style>
