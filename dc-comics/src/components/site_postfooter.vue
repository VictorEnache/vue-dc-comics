<template>
    <div id="postfooter">
        <div class="container">
            <button>SIGN-UP NOW!</button>
            <div class="social">
                <h3>FOLLOW US</h3>
                <ul>
                    <li><img src="../assets/img/footer-twitter.png" alt=""></li>
                    <li><img src="../assets/img/footer-twitter.png" alt=""></li>
                    <li><img src="../assets/img/footer-twitter.png" alt=""></li>
                    <li><img src="../assets/img/footer-twitter.png" alt=""></li>
                    <li><img src="../assets/img/footer-twitter.png" alt=""></li>
                </ul>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: 'site_prefooter'
}
</script>

<style lang="scss">
    #postfooter{
        background-color: rgb(24, 24, 24);
        .container{
            width: 1080px;
            margin: auto;
            padding: 2rem 0;
            display: flex;
            justify-content: space-between;
            align-items: center;

            button{
                border: none;
                padding: 1rem;
                background-color: transparent;
                color: white;
                border: 1px solid blue;
            }

            .social{
                display: flex;
                align-items: center;
                column-gap: 2rem;

                h3{
                    color: blue;
                }

                ul{
                    list-style: none;
                    display: flex;
                    column-gap: 2rem;
                }
            }
        }
    }
</style>