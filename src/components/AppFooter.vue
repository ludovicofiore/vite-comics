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
         <section>

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
</style>
