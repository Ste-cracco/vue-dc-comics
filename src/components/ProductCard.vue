<template>
    <article class="card">
        <img :src="src" :alt="titolo">
        <h2> {{ titolo }} </h2>
    </article>
</template>

<script>    
    export default {
        props: {
            src: String,
            titolo: String,
        },       
    }
</script>

<style lang="scss" scoped>

    .card {
        
        h2 {
            margin-top: -120px;
            font-size: 16px;
            text-align: center;
            text-transform: uppercase;
        }
    }
</style>