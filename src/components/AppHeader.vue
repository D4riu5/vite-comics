<script>

export default {
    name: 'AppHeader',
    components: {

    },
    data() {
        return {
            links: [
                {
                    label: 'CHARACTERS',
                    url: '#nogo',
                    active: false,
                },
                {
                    label: 'COMICS',
                    url: '#nogo',
                    active: true,
                },
                {
                    label: 'MOVIES',
                    url: '#nogo',
                    active: false,
                },
                {
                    label: 'COMICS',
                    url: '#nogo',
                    active: false,
                },
                {
                    label: 'MOVIES',
                    url: '#nogo',
                    active: false,
                },
                {
                    label: 'TV',
                    url: '#nogo',
                    active: false,
                },
                {
                    label: 'GAMES',
                    url: '#nogo',
                    active: false,
                },
                {
                    label: 'COLLECTIBLES',
                    url: '#nogo',
                    active: false,
                },
                {
                    label: 'VIDEOS',
                    url: '#nogo',
                    active: false,
                },
                {
                    label: 'FANS',
                    url: '#nogo',
                    active: false,
                },
                {
                    label: 'NEWS',
                    url: '#nogo',
                    active: false,
                },
                {
                    label: 'SHOP',
                    url: '#nogo',
                    active: false,
                },

            ]
        };
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
                <a v-for="link in links" :href="link.url" :class="{ 'active': link.active == true}">
                    {{ link.label }}
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
