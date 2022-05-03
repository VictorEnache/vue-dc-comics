<template>
    <header id="SiteHeader">
        <div class="container">
            <div class="logo">
                <img src="../assets/img/dc-logo.png" alt="">
            </div>
            <nav>
                <ul>
                    <li>CHARACTERS</li>
                    <li>COMICS</li>
                    <li>MOVIES</li>
                    <li>TV</li>
                    <li>GAMES</li>
                    <li>COLLECTIBLES</li>
                    <li>VIDEOS</li>
                    <li>FANS</li>
                    <li>NEWS</li>
                    <li>SHOP</li>
                </ul>
            </nav>
        </div>
    </header>
</template>

<script>


export default {
    name: 'SiteHeader'
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
                 column-gap: 1rem;
                 align-items: center;
                 
             }
         }
     }
 }
</style>
