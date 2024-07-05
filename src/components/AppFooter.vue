<script>
    export default {
        name: 'AppFooter',
    }
</script>

<template>
    <footer>
        <!-- section con bg -->
        <section class="icon-bg">
            <div class="container">

                <div class="col-container">

                    <div class="col">
                        <div class="list">
                            <!-- lista sopra -->
                            <h3>DC COMICS</h3>
                            <ul>
                                <li>
                                    <a href="#">Comics</a>
                                </li>
                                <li>
                                    <a href="#">Comics</a>
                                </li>
                                <li>
                                    <a href="#">Comics</a>
                                </li>
                                <li>
                                    <a href="#">Comics</a>
                                </li>
                                <li>
                                    <a href="#">Comics</a>
                                </li>
                                <li>
                                    <a href="#">Comics</a>
                                </li>
                                <li>
                                    <a href="#">Comics</a>
                                </li>
                            </ul>

                        </div>
                        <!-- lista sotto prima col -->
                        <div class="list">
                            <h3>SHOP</h3>
                            <ul>
                                <li>
                                    <a href="#">Comics</a>
                                </li>
                                <li>
                                    <a href="#">Comics</a>
                                </li>
                            </ul>
                        </div>

                    </div>

                    <div class="col">
                        <!-- lista seconda col -->
                        <div class="list">
                            <h3>DC</h3>
                            <ul>
                                <li>
                                    <a href="#">Comics</a>
                                </li>
                                <li>
                                    <a href="#">Comics</a>
                                </li>
                                <li>
                                    <a href="#">Comics</a>
                                </li>
                                <li>
                                    <a href="#">Comics</a>
                                </li>
                                <li>
                                    <a href="#">Comics</a>
                                </li>
                                <li>
                                    <a href="#">Comics</a>
                                </li>
                                <li>
                                    <a href="#">Comics</a>
                                </li>
                                <li>
                                    <a href="#">Comics</a>
                                </li>
                                <li>
                                    <a href="#">Comics</a>
                                </li>
                                <li>
                                    <a href="#">Comics</a>
                                </li>
                                <li>
                                    <a href="#">Comics</a>
                                </li>
                            </ul>
                        </div>

                    </div>

                    <div class="col">
                        <!-- lista terza col -->
                        <div class="list">
                            <h3>SITES</h3>
                            <ul>
                                <li>
                                    <a href="#">Comics</a>
                                </li>
                                <li>
                                    <a href="#">Comics</a>
                                </li>
                                <li>
                                    <a href="#">Comics</a>
                                </li>
                                <li>
                                    <a href="#">Comics</a>
                                </li>
                                <li>
                                    <a href="#">Comics</a>
                                </li>
                            </ul>
                        </div>

                    </div>

                </div>

                

                <!-- immagine logo footer -->
                 <div class="image-container">
                    <img src="../assets/img/dc-logo-bg.png" alt="logo dc footer">
                 </div>
            </div>

        </section>

        <!-- section finale -->
         <section id="final-section">
            <div class="container">

                <div class="sign-button">
                    <a href="#">
                        SIGN-UP NOW!
                    </a>
                </div>

                <div class="social">
                    <span>FOLLOW US</span>

                    <ul>
                        <li>
                            <a href="#">
                                <img src="../assets/img/footer-facebook.png" alt="link facebook">
                            </a>
                        </li>
                        <li>
                            <a href="#">
                                <img src="../assets/img/footer-twitter.png" alt="link twitter">
                            </a>
                        </li>
                        <li>
                            <a href="#">
                                <img src="../assets/img/footer-youtube.png" alt="link youtube">
                            </a>
                        </li>
                        <li>
                            <a href="#">
                                <img src="../assets/img/footer-pinterest.png" alt="link pinterest">
                            </a>
                        </li>
                        <li>
                            <a href="#">
                                <img src="../assets/img/footer-periscope.png" alt="link periscope">
                            </a>
                        </li>
                    </ul>

                </div>
            </div>

         </section>
    </footer>
</template>




<style lang="scss" scoped>

.icon-bg {
    background-image: url(../assets/img/footer-bg.jpg);
    background-size: cover;
    width: 100%;
    // height: 500px;
    color: white;

    .container {
        display: flex;
        justify-content: space-between;

        .col-container {
            display: flex;
            gap: 30px;
            padding: 50px 0;
        }

        .image-container {
            width: 30%;

            img {
                max-width: 100%;
            }
        }
    }
}


#final-section {
    background-color: rgb(48, 48, 48);

    .container {
        display: flex;
        justify-content: space-between;
        padding: 50px 0; 

        .social {
            display: flex;
            align-items: center;

            ul {
                display: flex;
                gap: 20px;
            }
        }
    }
}
</style>
