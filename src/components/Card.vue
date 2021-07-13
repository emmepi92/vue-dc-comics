<template>
    <div class="card-container">
        <div class="comic-name"> {{ comic.series }}</div>
        <img :src="comic.thumb" alt="">
        <div class="comic-price">{{ comic.price }}</div>       
    </div>
</template>

<script>


export default {
    name: "Card",
    props: {
        comic:Object
    }
}
</script>

<style lang="scss" scoped>
    .card-container {
        width: calc(100% / 6);
        padding: 30px 20px;

        img {
            width: 100%;
            
        }

        .comic-name {
            height: 50px;
            text-align: center;
        }

        .comic-price {
            text-align: end;
        }


    }


</style>