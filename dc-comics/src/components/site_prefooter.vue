<template>
    <div id="site_prefooter">
        <div class="container">
            <nav>
                <ul>
                    <li><img src="../assets/img/buy-comics-digital-comics.png" alt=""><span>DIGITAL COMICS</span></li>
                    <li><img src="../assets/img/buy-comics-merchandise.png" alt=""><span>DIGITAL COMICS</span></li>
                    <li><img src="../assets/img/buy-comics-digital-comics.png" alt=""><span>DIGITAL COMICS</span></li>
                    <li><img src="../assets/img/buy-comics-digital-comics.png" alt=""><span>DIGITAL COMICS</span></li>
                    <li><img src="../assets/img/buy-comics-digital-comics.png" alt=""><span>DIGITAL COMICS</span></li>
                </ul>
            </nav>
        </div>
    </div>
</template>

<script>


export default {
    name: 'site_prefooter'
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
                    justify-content: space-between;
                    padding: 50px 0;

                    li{
                        height: 55px;
                        display: flex;
                        align-items: center;
                        font-size:14px;
                        color: white;
                        

                        img{
                            height: 100%;
                            object-fit: cover;
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
