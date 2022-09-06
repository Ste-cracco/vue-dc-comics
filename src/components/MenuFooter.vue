<template>
    <div class="menu_footer">
        <ul>
            <li v-for="(link, index) in links" :key="index" >
                <a :class="[link.title === true ? 'title' : '']"> {{ link.testo }}</a>
            </li>    
        </ul>
    </div>
</template>

<script>   

    export default {
        props: {
            links: Array
        }
    }

</script>

<style lang="scss" scoped>
 @import '../style/footer_middle.scss';
    
</style>