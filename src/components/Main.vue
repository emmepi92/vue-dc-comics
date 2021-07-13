<template>
    <div class="fluid-container">
        <div class="container">
            <Card v-for="comic in comics" :key="comic.series" :comic = 'comic' />
        </div>

    </div>    
</template>

<script>
import Card from './Card.vue';
import comicsJson from "../jsons/dc-comics.json"

export default {
    name:"Main",
    components: {
        Card
    },
    data: function () {
        return {
            comics:comicsJson
        }
    }
}
</script>


<style lang="scss" scoped>
    .fluid-container {
        background-color: black;
            padding: 50px 0;

        .container {
            color: white;
            display: flex;
            flex-wrap: wrap;
        }

    }

</style>