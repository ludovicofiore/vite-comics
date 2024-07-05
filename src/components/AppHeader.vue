<script>
    export default {
        name: 'AppHeader',
    }
</script>

<template>
    <header>
        <div class="row container">

            <span id="header-logo">
                <img src="../assets/img/dc-logo.png" alt="logo DC">
            </span>
            <ul>
                <li>
                    <a href="#">COMICS</a>
                </li>
                <li>
                    <a href="#">COMICS</a>
                </li>
                <li>
                    <a href="#">COMICS</a>
                </li>
                <li>
                    <a href="#">COMICS</a>
                </li>
                <li>
                    <a href="#">COMICS</a>
                </li>
                <li>
                    <a href="#">COMICS</a>
                </li>
                <li>
                    <a href="#">COMICS</a>
                </li>
                <li>
                    <a href="#">COMICS</a>
                </li>
                <li>
                    <a href="#">COMICS</a>
                </li>
                <li>
                    <a href="#">COMICS</a>
                </li>
            </ul>
        </div>
       
    </header>
</template>

<style lang="scss" scoped>

header {
    background-color: white;

}

.row {

    
    display: flex;
    justify-content: space-between;
    align-items: center;
    
    ul {
        display: flex;
        gap: 15px;

    }
}
</style>