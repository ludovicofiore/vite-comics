<script>
    export default {
        name: 'AppBlueSection',
    }
</script>


<template>
<section>
    <div class="container">

        <div class="card">
            <div class="image-container">
                <img src="../assets/img/buy-comics-digital-comics.png" alt="immagine fumetto">
            </div>

            <div class="card-text">
                <a href="#">DIGITAL COMICS</a>
            </div>
        </div>

        <div class="card">
            <div class="image-container">
                <img src="../assets/img/buy-comics-merchandise.png" alt="immagine fumetto">
            </div>

            <div class="card-text">
                <a href="#">DC MERCHANDISE</a>
            </div>
        </div>

        <div class="card">
            <div class="image-container">
                <img src="../assets/img/buy-comics-subscriptions.png" alt="immagine fumetto">
            </div>

            <div class="card-text">
                <a href="#">SUBSCRIPTIONS</a>
            </div>
        </div>

        <div class="card">
            <div class="image-container">
                <img src="../assets/img/buy-comics-shop-locator.png" alt="immagine fumetto">
            </div>

            <div class="card-text">
                <a href="#">COMIC SHOP LOCATOR</a>
            </div>
        </div>

        <div class="card">
            <div class="image-container">
                <img src="../assets/img/buy-dc-power-visa.svg" alt="immagine fumetto">
            </div>

            <div class="card-text">
                <a href="#">DC POWER VISA</a>
            </div>
        </div>

    </div>

</section>
</template>


<style lang="scss" scoped>
@use '../styles/partials/variables' as *;

section {
    width: 100%;
    background-color: $dc-blue;

    .container {
        display: flex;
        justify-content: center;
        padding: 50px 0;

        .card {
            display: flex;
            justify-content: center;
            align-items: center;
            width: calc(100% / 5);

            .image-container {
                width: 50px;

                img {
                    max-width: 100%;
                }
            }

            .card-text a {
                color: white;
                padding-left: 15px;
            }
        }
    }

}

</style>