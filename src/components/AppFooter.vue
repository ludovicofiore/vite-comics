<script>
    export default {
        name: 'AppFooter',

        // aggiungo struttura dati
        data() {
            return {
                linksComics: [
                    {
                        text: "Characters",
                        url: "#",
                    },
                    {
                        text: "Comics",
                        url: "#",
                    },
                    {
                        text: "Movies",
                        url: "#",
                    },
                    {
                        text: "TV",
                        url: "#",
                    },
                    {
                        text: "Games",
                        url: "#",
                    },
                    
                    {
                        text: "Videos",
                        url: "#",
                    },
                    {
                        text: "Fans",
                        url: "#",
                    },
                    {
                        text: "News",
                        url: "#",
                    },
                    
                ],

                linksShop: [
                    {
                        text: "Shop DC",
                        url: "#",
                    },
                    {
                        text: "Shop DC Collectibles",
                        url: "#",
                    },
                    
                ],

                linksDC: [
                    {
                        text: "Characters",
                        url: "#",
                    },
                    {
                        text: "Comics",
                        url: "#",
                    },
                    {
                        text: "Movies",
                        url: "#",
                    },
                    {
                        text: "TV",
                        url: "#",
                    },
                    {
                        text: "Games",
                        url: "#",
                    },
                    
                    {
                        text: "Videos",
                        url: "#",
                    },
                    {
                        text: "Fans",
                        url: "#",
                    },
                    {
                        text: "News",
                        url: "#",
                    },
                    {
                        text: "Games",
                        url: "#",
                    },
                    
                    {
                        text: "Videos",
                        url: "#",
                    },
                    {
                        text: "Fans",
                        url: "#",
                    },
                    {
                        text: "News",
                        url: "#",
                    },
                    
                ],

                linksSites: [
                    {
                        text: "Characters",
                        url: "#",
                    },
                    {
                        text: "Comics",
                        url: "#",
                    },
                    {
                        text: "Movies",
                        url: "#",
                    },
                    {
                        text: "TV",
                        url: "#",
                    },
                    {
                        text: "Games",
                        url: "#",
                    },
                    
                    {
                        text: "Videos",
                        url: "#",
                    },
                    
                ],
            }
        }
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
                                <li v-for="(link, i) in linksComics" :key="i">
                                    <a :href="link.url">{{ link.text }}</a>
                                </li>
                            </ul>

                        </div>
                        <!-- lista sotto prima col -->
                        <div class="list">
                            <h3>SHOP</h3>
                            <ul>
                                <li v-for="(link, i) in linksShop" :key="i">
                                    <a :href="link.url">{{ link.text }}</a>
                                </li>
                               
                            </ul>
                        </div>

                    </div>

                    <div class="col">
                        <!-- lista seconda col -->
                        <div class="list">
                            <h3>DC</h3>
                            <ul>
                                <li v-for="(link, i) in linksDC" :key="i">
                                    <a :href="link.url">{{ link.text }}</a>
                                </li>
                               
                            </ul>
                        </div>

                    </div>

                    <div class="col">
                        <!-- lista terza col -->
                        <div class="list">
                            <h3>SITES</h3>
                            <ul>
                                <li v-for="(link, i) in linksSites" :key="i">
                                    <a :href="link.url">{{ link.text }}</a>
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
@use '../styles/partials/variables' as *;
@use '../styles/partials/mixins' as *;

.icon-bg {
    background-image: url(../assets/img/footer-bg.jpg);
    background-size: cover;
    width: 100%;
    color: white;

    .container {
        @include center(horizontal);
        justify-content: space-between;

        .col-container {
            display: flex;
            gap: 30px;
            padding: 50px 0;

            .list {
                margin-bottom: 20px;

                h3 {
                    margin-bottom: 15px;
                }

                a {
                    display: inline-block;
                    color: rgb(122, 122, 122);
                    padding: 3px 0;
                    
                    
                }
            }
           

           
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
        @include center(horizontal);
        justify-content: space-between;
        padding: 50px 0; 

        .sign-button a {
            display: inline-block;
            color: white;
            font-weight: bold;
            padding: 10px;
            border: 2px solid $dc-blue;
        }

        .social {
            @include center(horizontal);

            span {
                color: $dc-blue;
                margin-right: 25px;
                font-weight: bold;
            }

            ul {
                display: flex;
                gap: 20px;
            }
        }
    }
}
</style>
