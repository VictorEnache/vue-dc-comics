<template>
    <div id="site_prefooter">
        <div class="container">
            <nav>
                <ul>
                    <li :key='card' v-for='card in cards'><img :src="card.link" alt=""><span>{{card.name}}</span></li>
                </ul>
            </nav>
        </div>
    </div>
</template>

<script>


export default {
    name: 'site_prefooter',

    data() {
        return{
            cards:[
                {
                    link: require("../assets/img/buy-comics-digital-comics.png"),
                    name: 'DIGITAL COMICS'
                },
                                {
                    link: require("../assets/img/buy-comics-merchandise.png"),
                    name: 'DC MERCHANDISE'
                },
                                {
                    link: require("../assets/img/buy-comics-subscriptions.png"),
                    name: 'SUBSCRIPTION'
                },
                                {
                    link: require("../assets/img/buy-comics-shop-locator.png"),
                    name: 'COMIC SHOP LOCATOR'
                },
                                {
                    link: require("../assets/img/buy-dc-power-visa.svg"),
                    name: 'DC POWER VISA'
                },
            ]
        }
    }
}
</script>

<style lang="scss">
    #site_prefooter{
        background-color: blue;

        .container{
            width: 1080px;
            margin: auto;

            nav{

                ul{
                    list-style: none;
                    display: flex;
                    
                    padding: 50px 0;
                    

                    li{         
                        width: calc(100%/5);              
                        display: flex;
                        align-items: center;
                        font-size:12px;
                        color: white;
                        

                        img{
                            
                            height: 55px;
                            width: 55px;
                            object-fit: contain;
                        }

                        span{
                            padding: 0 1rem;
                        }
                    }
                }
            }
        }
    }
</style>
