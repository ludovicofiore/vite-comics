<script>
    export default {
        name: 'AppHeader',

        // aggiungo struttura dati
        data() {
            return {
                links: [
                    {
                        text: "CHARACTERS",
                        url: "#",
                        current: false
                    },
                    {
                        text: "COMICS",
                        url: "#",
                        current: true
                    },
                    {
                        text: "MOVIES",
                        url: "#",
                        current: false
                    },
                    {
                        text: "TV",
                        url: "#",
                        current: false
                    },
                    {
                        text: "GAMES",
                        url: "#",
                        current: false
                    },
                    {
                        text: "COLLECTIBLES",
                        url: "#",
                        current: false
                    },
                    {
                        text: "VIDEOS",
                        url: "#",
                        current: false
                    },
                    {
                        text: "FANS",
                        url: "#",
                        current: false
                    },
                    {
                        text: "NEWS",
                        url: "#",
                        current: false
                    },
                    {
                        text: "SHOP",
                        url: "#",
                        current: false
                    },
                ]
            }
        }
    }
</script>

<template>
    <header>
        <div class="row container">

            <span id="header-logo">
                <img src="../assets/img/dc-logo.png" alt="logo DC">
            </span>

            <ul>
                <li v-for="(link, index) in links" :key="index">
                    <a :href="link.url" :class="link.current ? 'active' : ''">{{ link.text }}</a>
                    
                </li>
               
            </ul>
        </div>
       
    </header>

    <div id="jumbotron">
        <img src="../assets/img/jumbotron.jpg" alt="jumbotron">
    </div>
</template>

<style lang="scss" scoped>
@use '../styles/partials/variables' as *;
@use '../styles/partials/mixins' as *;

header {
    background-color: white;
    height: 150px;
}

.row {

    height: 100%;
    @include center(horizontal);
    justify-content: space-between;
    
    ul {
        display: flex;
        flex-wrap: wrap;
        gap: 15px;
        height: 100%;

        a {
            display: inline-block;
            color: black;
            font-weight: bold;
            height: 100%;
            padding-top: 70px;

            &.active,
            &:hover {
                color: $dc-blue;
                border-bottom: 5px solid $dc-blue;
            }
        }


    }
}


#jumbotron {
    width: 100%;
    height: 450px;

    img {
        width: 100%;
        height: 100%;
        object-fit: fill;
    }
}
</style>