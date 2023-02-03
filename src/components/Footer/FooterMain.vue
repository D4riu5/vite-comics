<script>

export default {
    name: 'FooterMain',
}
</script>


<template>
    <main class="bg-secondary py-5">
        <div class="container d-flex justify-content-between">
            <div class="d-flex">
                <div class="d-flex flex-row">
                    <div class="pe-4">
                        <div class="d-flex flex-column">
                            <h5>
                                DC COMICS
                            </h5>
                            <span>
                                Characters
                            </span>
                            <span>
                                Comics
                            </span>
                            <span>
                                Movies
                            </span>
                            <span>
                                TV
                            </span>
                            <span>
                                Games
                            </span>
                            <span>
                                Videos
                            </span>
                            <span>
                                News
                            </span>
                        </div>
                        <div class="d-flex flex-column py-3">
                            <h5>
                                SHOP
                            </h5>
                            <span>
                                Shop DC
                            </span>
                            <span>
                                Shop DC Collectibles
                            </span>
                        </div>
                    </div>
                    
                    <div class="d-flex flex-column pe-4">
                        <h5>
                            Terms Of Use
                        </h5>
                        <span>
                            Privacy policy (New)
                        </span>
                        <span>
                            Ad Choices
                        </span>
                        <span>
                            Advertising
                        </span>
                        <span>
                            Jobs
                        </span>
                        <span>
                            Subscriptions
                        </span>
                        <span>
                            Talent Workshops
                        </span>
                        <span>
                            CPSC Certificates
                        </span>
                        <span>
                            Ratings
                        </span>
                        <span>
                            Shop Help
                        </span>
                        <span>
                            Contact Us
                        </span>
                    </div>
                    <div class="d-flex flex-column">
                        <h5>
                            SITES
                        </h5>
                        <span>
                            DC
                        </span>
                        <span>
                            MAD Magazine
                        </span>
                        <span>
                            DC Kids
                        </span>
                        <span>
                            DC Universe
                        </span>
                        <span>
                            DC Power Visa
                        </span>
                    </div>
                </div>
            </div>
            <div class="position-relative my_img_container">
                <img src="../../assets/img/dc-logo-bg.png" alt="">
            </div>
        </div>
    </main>
</template>


<style lang="scss" scoped>
main{
    background-image: url(../../assets/img/footer-bg.jpg);
    background-size: cover;

    h5{
        color: white;
        font-size: 15px;
        font-weight: bold;
    }

    span{
        color:gray;
        font-size: 12px;
        padding: 2px 0;
    }

    .my_img_container{
        width: 300px;
    }


    img{
        width: 500px;
        aspect-ratio: 1/1;
        position: absolute;
        left: -200px;
        top: -100px;
        z-index: 0;
    }
}

</style>
