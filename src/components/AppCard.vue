<script>
    export default {
        name: 'AppCard',
        props: {
            comicsContent: Object
        }
    }
</script>


<template>
    <div class="card">
        <div class="card-image">
            <img :src="comicsContent.thumb" alt="">
        </div>

        <div class="card-text">
            <h3>{{ comicsContent.series }}</h3>
        </div>
    </div>

</template>


<style lang="scss" scoped>

.card {
    flex-basis: calc(100% / 6 - 30px);
    margin-bottom: 20px;

    .card-image {
        width: 100%;
        

        img {
            width: 100%;
            height: 200px;
        }
    }
    
    

    .card-text {
        margin-top: 20px;
    }
}
</style>