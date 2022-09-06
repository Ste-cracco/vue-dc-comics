<template>
    <article class="card">
        <img :src="comics[0].src" alt="">
        <h2> {{ comics[0].titolo }} </h2>
    </article>
</template>

<script>
    
    export default {
        
    }

</script>

<style lang="scss" scoped>

    .card {
        background: white;
        height: 50px;
    }
</style>