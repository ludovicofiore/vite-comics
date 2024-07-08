<script>
    export default {
        name: 'AppCard'
    }
</script>


<template>
    <div class="card">
        <div class="card-image">
            <img src="https://www.coverbrowser.com/image/action-comics/1-1.jpg" alt="">
        </div>

        <div class="card-text">
            <span>action comics</span>
        </div>
    </div>

</template>


<style lang="scss" scoped>

.card {
    width: calc(100% / 6);

    .card-image img {
        max-width: 100%;
    }

    .card-text {
        margin-top: 20px;
    }
}
</style>