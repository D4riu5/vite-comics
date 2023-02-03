<script>

export default {
    name: 'FooterFooter',
    components: {

    }
}
</script>


<template>
    <footer class="text-white py-4 position-relative">
        <div class="container d-flex justify-content-between">
                <a id="sign-up-link" class="p-2" href="#nogo">
                    SING-UP NOW!
                </a>
            <div class="d-flex align-items-center">
                <a href="#nogo">
                    FOLLOW US
                </a>
                <a href="#nogo">
                    <img src="../../assets/img/footer-facebook.png" alt="">
                </a>
                <a href="#nogo">
                    <img src="../../assets/img/footer-twitter.png" alt="">
                </a>
                <a href="#nogo">
                    <img src="../../assets/img/footer-youtube.png" alt="">
                </a>
                <a href="#nogo">
                    <img src="../../assets/img/footer-pinterest.png" alt="">
                </a>
                <a href="#nogo">
                    <img src="../../assets/img/footer-periscope.png" alt="">
                </a>
            </div>
        </div>
    </footer>
</template>


<style lang="scss" scoped>
footer{
    background-color: #303030;
    z-index: 1;

    #sign-up-link{
        border: solid 2px #0282F9;
        text-decoration: none;
        color: white;
        font-size: 15px;
    }
    
    a{
        text-decoration: none;
        color: #0282F9;
        font-size: 15px;
        padding: 0 5px;
    }

    img{
        width: 25px;
        aspect-ratio: 1/1;
    }

}
</style>
