<script>
import MainJumbo from './Main/MainJumbo.vue';
import MainCard from './Main/MainCard.vue';
import DcComics from '../data/dc-comics.json';

export default {
    name: 'AppMain',
    components: {
        MainJumbo,
        MainCard,
    },
    data() {
        return {
            comics: DcComics,
        }
    }
}
</script>


<template>
    <MainJumbo/>

    <main class="bg-dark text-white pt-5 pb-3">
        <div class="container position-relative">
            <div class="my_preview-btn my_floating py-2 px-4 ">
                CURRENT SERIES
            </div>
            <div>
                <div class="my_cards d-flex flex-wrap">
                <MainCard v-for="element in comics"
                :thumb="element.thumb"
                :title="element.series"/>
                </div>
            </div>
        </div>
        <div class="d-flex justify-content-center pt-2">
            <div class="my_preview-btn py-2 px-5">
                LOAD MORE
            </div>
        </div>
    </main>
    
</template>


<style lang="scss" scoped>
.my_preview-btn{
    display: inline-block;
    color: white;
    background-color: #0282F9;
    font-size: 12px;
    font-weight: bold;

    &.my_floating{
        position: absolute;
        top: -68px;
        font-size: 15px;
    }

}

</style>
