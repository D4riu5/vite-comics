<script>

export default {
    name: 'MainCard',
    props: {
        thumb: String,
        title: String,

    }
}
</script>


<template>
    <div class="my_card px-3">
        <div>
            <img :src="thumb" :alt="title">
        </div>
        <h5 class="py-2">
            {{ title }}
        </h5>
    </div>
</template>


<style lang="scss" scoped>
.my_card{
    width: calc(100%/6);

    img{
        width: 100%;
        aspect-ratio: 1/1;
        object-fit: cover;
        object-position: 0 0;
    }

    h5{
        font-size: 12px;
        text-transform: uppercase;
    }
}
    
    
   


</style>
