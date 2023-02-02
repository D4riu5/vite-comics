<script>
import FooterHeader from './Footer/FooterHeader.vue';
import FooterMain from './Footer/FooterMain.vue';
import FooterFooter from './Footer/FooterFooter.vue';
export default {
    name: 'AppFooter',
    components: {
        FooterHeader,
        FooterMain,
        FooterFooter,
    }
}
</script>


<template>
    <FooterHeader/>
    <FooterMain/>
    <FooterFooter/>
</template>


<style scoped>
</style>
