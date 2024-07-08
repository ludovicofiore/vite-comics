<script>
    export default {
        name: 'AppContent',
    }
</script>

<template>
<div class="container">
    <div class="series">
        <h2>CURRENT SERIES</h2>
    </div>


    <div class="button">
        <span>LOAD MORE</span>
    </div>
</div>

</template>

<style lang="scss" scoped>
@use '../styles/partials/variables' as *;


.container {
    height: 200px;
    color: white;
    position: relative;


    .series {
        background-color: $dc-blue;
        color: white;
        padding: 5px 10px;
        display: inline-block;
        position: absolute;
        top: -20px;
    }


    .button {
        display: flex;
        justify-content: center;
        padding: 25px 0;

        span {
            background-color: $dc-blue;
            color: white;
            padding: 5px 30px;
            cursor: pointer;
        }
    }
}

</style>