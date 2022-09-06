<template>
    <ul class="menu">
        <li v-for="(link, index) in links" :key="index" >
            <a :class="[link.current === true ? 'active' : '']" :href="link.href"> {{ link.testo }}</a>
        </li>        
    </ul>
</template>

<script>   

    export default {
        props: {
            links: Array
        }
    }

</script>

<style lang="scss" scoped>

    .menu {
            display: flex;
            align-items: center;
            text-transform: uppercase;
            margin-left: auto;
            gap: 25px;
        }

        li {
            font-weight: bold;
            color: #464646;
            font-size: 14px;

            a.active, a:hover {
                border-bottom: 5px solid #0282F9;
                color: #0282F9;
                padding-bottom: 52px;                
            }
        }
    
</style>