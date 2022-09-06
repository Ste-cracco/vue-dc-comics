<template>
   <header>
        <div class="container">
            <div class="logo">
                <img src="../assets/img/dc-logo.png" alt="Logo">
            </div>
            <MenuHeader :links="menu"/>
        </div>
</header>
</template>

<script>
import MenuHeader from './MenuHeader.vue'

    export default {
        components: {
        MenuHeader,    
        },
        data() {
            return {
                menu: [
                    {
                        testo: 'Characters',
                        href: '#'
                    },
                    {
                        testo: 'Comics',
                        href: '#'
                    },
                    {
                        testo: 'Movies',
                        href: '#'
                    },
                    {
                        testo: 'TV',
                        href: '#'
                    },
                    {
                        testo: 'Games',
                        href: '#'
                    },
                    {
                        testo: 'Collectible',
                        href: '#'
                    },
                    {
                        testo: 'Videos',
                        href: '#'
                    },
                    {
                        testo: 'Fans',
                        href: '#'
                    },
                    {
                        testo: 'News',
                        href: '#'
                    },
                    {
                        testo: 'Shop',
                        href: '#'
                    },
                ]
            }
        }

    }
</script>

<style lang="scss" scoped>

    .container {
        display: flex; 
        max-width: 1200px;
        margin: auto;
        
        .logo {
            padding: 20px
        }

        img {
            height: 85px;
        }
    }
    
</style>