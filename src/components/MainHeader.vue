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
                        href: '#',
                        current: false
                    },
                    {
                        testo: 'Comics',
                        href: '#',
                        current: true
                    },
                    {
                        testo: 'Movies',
                        href: '#',
                        current: false
                    },
                    {
                        testo: 'TV',
                        href: '#',
                        current: false
                    },
                    {
                        testo: 'Games',
                        href: '#',
                        current: false
                    },
                    {
                        testo: 'Collectible',
                        href: '#',
                        current: false
                    },
                    {
                        testo: 'Videos',
                        href: '#',
                        current: false
                    },
                    {
                        testo: 'Fans',
                        href: '#'
                    },
                    {
                        testo: 'News',
                        href: '#',
                        current: false
                    },
                    {
                        testo: 'Shop',
                        href: '#',
                        current: false
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