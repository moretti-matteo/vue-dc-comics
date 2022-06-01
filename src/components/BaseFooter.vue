<template>
    <footer class="footer">

        <div class="footer__top">
            <div class="container">
                <nav>
                    <ul>
                        <li>
                            <img src="../assets/img/buy-comics-digital-comics.png" alt="">
                            <a href="#">DIGITAL COMICS</a>
                        </li>
                        <li>
                            <img src="../assets/img/buy-comics-merchandise.png" alt="">

                            <a href="#">DC MERCHANDISE</a>
                        </li>
                        <li>
                            <img src="../assets/img/buy-comics-subscriptions.png" alt="">

                            <a href="#">SUBSCRIPTION</a>
                        </li>
                        <li>
                            <img src="../assets/img/buy-comics-shop-locator.png" alt="">

                            <a href="#">COMIC SHOP LOCATOR</a>
                        </li>
                        <li>
                            <img src="../assets/img/buy-dc-power-visa.svg" alt="">

                            <a href="#">DC POWER VISA</a>
                        </li>
                    </ul>
                </nav>
            </div>

        </div>
        <div class="footer__middle">
            <div class="container">
                <div class="nav">
                    <div class="nav-left">
                        <nav>
                            <h3>DC COMICS</h3>
                            <ul>
                                <li><a href="#">Characters</a></li>
                                <li><a href="#">Comics</a></li>
                                <li><a href="#">Movies</a></li>
                                <li><a href="#">TV</a></li>
                                <li><a href="#">Games</a></li>
                                <li><a href="#">Videos</a></li>
                                <li><a href="#">News</a></li>
                            </ul>
                        </nav>

                        <nav>
                            <h3>SHOP</h3>
                            <ul>
                                <li><a href="#">Shop DC</a></li>
                                <li><a href="#">Shop DC Collectibles</a></li>
                            </ul>
                        </nav>
                    </div>
                    <div class="nav-middle">
                        <nav>
                            <h3>DC</h3>
                            <ul>
                                <li><a href="#">Terms of use</a></li>
                                <li><a href="#">Privay policy</a></li>
                                <li><a href="#">Ad choices</a></li>
                                <li><a href="#">Advertising</a></li>
                                <li><a href="#">Jobs</a></li>
                                <li><a href="#">Subscription</a></li>
                                <li><a href="#">Talent workshop</a></li>
                                <li><a href="#">Talent workshop</a></li>
                                <li><a href="#">Talent workshop</a></li>
                                <li><a href="#">Talent workshop</a></li>
                                <li><a href="#">Talent workshop</a></li>
                            </ul>
                        </nav>
                    </div>
                    <div class="nav-right">
                        <nav>
                            <h3>SITES</h3>
                            <ul>
                                <li><a href="#">DC</a></li>
                                <li><a href="#">Privay policy</a></li>
                                <li><a href="#">Ad choices</a></li>
                                <li><a href="#">Advertising</a></li>
                                <li><a href="#">Jobs</a></li>

                            </ul>
                        </nav>
                    </div>
                </div>

                <div class="">
                    <img src="../assets/img/dc-logo-bg.png" alt="">
                </div>
            </div>
        </div>
        <div class="footer__bottom">
            <div class="container">
                <div class="footer__bottom__left">
                    <button>SIGN-UP NOW!</button>
                </div>
                <div class="footer__bottom__right">
                    <h4>FOLLOW US</h4>
                    <img src="../assets/img/footer-facebook.png" alt="">
                    <img src="../assets/img/footer-periscope.png" alt="">
                    <img src="../assets/img/footer-pinterest.png" alt="">
                    <img src="../assets/img/footer-twitter.png" alt="">
                    <img src="../assets/img/footer-youtube.png" alt="">
                </div>
            </div>
        </div>

    </footer>
</template>

<script>
export default {
    name: 'BaseFooter'
}
</script>

<style lang="scss">
.footer {

    &__top {
        background-color: #0282f9;
        padding: 40px 0;

        ul {
            display: flex;
            list-style-type: none;
            justify-content: space-evenly;

            li {
                display: flex;
                align-items: center;
            }

            img {
                width: 40px;
                margin-right: 10px;
            }

            a {
                color: var(--text-white);
                text-decoration: none;
            }
        }
    }

    &__middle {
        background-image: url("../assets/img/footer-bg.jpg");
        background-size: cover;
        background-position: center;
        // max-height: 320px;

        ul {
            list-style-type: none;

            a {
                color: grey;
                text-decoration: none;
            }
        }

        .container {
            display: flex;
            justify-content: space-between;

            h3 {
                color: var(--text-white);
                margin-bottom: 15px;
                margin-top: 20px;
            }

            .nav {
                display: flex;
                column-gap: 30px;
            }

            div:last-child img {
                width: 320px;

            }




        }
    }

    &__bottom {
        background-color: #303030;
        padding: 20px;
        .container {
            display: flex;
            justify-content: space-between;
            align-content: center;

            button{
                color:white;
                background: none;
                border:1px solid #0282f9;
                padding: 10px;
            }

            h4{
                color:#0282f9;
                margin-right: 10px;
            }
            
        }

        &__right{
            display: flex;
            align-items:center;
            column-gap: 10px;
        }

    }

}
</style>