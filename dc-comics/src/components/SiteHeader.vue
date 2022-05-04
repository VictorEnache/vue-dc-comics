<template>
    <header id="SiteHeader">
        <div class="container">
            <div class="logo">
                <img src="../assets/img/dc-logo.png" alt="">
            </div>
            <nav>
                <ul>
                    <li :key='link' v-for='link in navigation'>{{link}}</li>
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

         .logo{
             width:80px;

             img{
                 width: 100%;
                 object-fit: cover;
                 display: block;
             }
         }

         nav{
             height:80px;
             

             ul{
                 height: 100%;
                 list-style: none;
                 display: flex;
                 column-gap: 0.5rem;
                 align-items: center;
                 font-size: 13px;
                 
             }
         }
     }
 }
</style>
