<script>

export default {
    name: 'FooterHeader',
}
</script>


<template>
    <header class=" text-white py-5">
       <div class="container d-flex px-5 justify-content-between">
            <div>
                <img src="../../assets/img/buy-comics-digital-comics.png" alt="">
                <span>DIGITAL COMICS</span>
            </div>
            <div>
                <img src="../../assets/img/buy-comics-merchandise.png" alt="">
                <span>DC MERCHANDISE</span>
            </div>
            <div>
                <img src="../../assets/img/buy-comics-subscriptions.png" alt="">
                <span>SUBSCRIPTION</span>
            </div>
            <div>
                <img src="../../assets/img/buy-comics-shop-locator.png" alt="">
                <span>COMIC SHOP LOCATOR</span>
            </div>
            <div>
                <img src="../../assets/img/buy-dc-power-visa.svg" alt="">
                <span>DC POWER VISA</span>
            </div>
       </div>
    </header>
</template>


<style lang="scss" scoped>
header{
    background-color: #0282F9;

    img{
    width: 40px;
    aspect-ratio: 1/1.1;
    }

    span{
        padding: 0 10px;
        font-size: 12px;
    }
}




</style>
