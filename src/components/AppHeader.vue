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
                <a href="#nogo">
                    CHARACTERS
                </a>
                <a class="active" href="#nogo">
                    COMICS
                </a>
                <a href="#nogo">
                    MOVIES
                </a>
                <a href="#nogo">
                    TV
                </a>
                <a href="#nogo">
                    GAMES
                </a>
                <a href="#nogo">
                    COLLECTIBLES
                </a>
                <a href="#nogo">
                    VIDEOS
                </a>
                <a href="#nogo">
                    FANS
                </a>
                <a href="#nogo">
                    NEWS
                </a>
                <a href="#nogo">
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
    
    &.active{
        border-bottom: solid 6px #0282F9;
        padding-bottom: 44px
    }
}

</style>
