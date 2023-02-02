<script>

export default {
    name: 'AppHeader',
    components: {

    }
}
</script>


<template>
    <header class="bg-white text-dark">
        <div class="container d-flex justify-content-between align-items-center">
            <div  id="logo">
                <img src="../assets/img/dc-logo.png" alt="">
            </div>
            <nav class="d-flex justify-content-between align-items-center">
                <a href="">
                    CHARACTERS
                </a>
                <a class="active" href="">
                    COMICS
                </a>
                <a href="">
                    MOVIES
                </a>
                <a href="">
                    TV
                </a>
                <a href="">
                    GAMES
                </a>
                <a href="">
                    COLLECTIBLES
                </a>
                <a href="">
                    VIDEOS
                </a>
                <a href="">
                    FANS
                </a>
                <a href="">
                    NEWS
                </a>
                <a href="">
                    SHOP
                </a>
            </nav>
        </div>
    </header>
</template>


<style lang="scss" scoped>
img{
    width: 75px;
    aspect-ratio: 1/1;
}

a{
    text-decoration: none;
    color: black;
    padding: 50px 10px;
    margin: 0 5px;
    font-size: 12px;
    font-weight: bold;
    
    
    &.active{
        border-bottom: solid 6px #0282F9;
        padding-bottom: 44px
    }
}

</style>
