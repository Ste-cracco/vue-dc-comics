<template>
    <main>
        <div class="jumbotron">

        </div>
        <div class="container">
            <ProductCard v-for="(comic, i) in comics" :key="i" :titolo="comic.titolo" :src="comic.src" :alt="comic.titolo"/> 
        </div>
    </main>
</template>

<script>
    import ProductCard from './ProductCard.vue'
    import comics from '../dc-comics'

    export default {
        components: {
            ProductCard
        },
        data() {
            return {
                comics: comics
            }
        },
        computed: {

        }
    }
</script>

<style lang="scss" scoped>
    main {
        background-color: #1C1C1C;
        color: white;
        font-weight: bold;
        line-height: 150px;

        .jumbotron {
            height: 400px;
            background-image: url('../assets/img/jumbotron.jpg');
        }

        .container {
            max-width: 1200px;
            margin: auto;
            display: grid;
            grid-template-columns: 1fr 1fr 1fr 1fr 1fr 1fr;
            gap: 20px;
            padding: 30px;
        }
    }
</style>