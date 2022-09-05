<template>
   <header>
        <div class="container">
            <div class="logo">
                <img src="../assets/img/dc-logo.png" alt="Logo">
            </div>
            <ul class="menu">
                <li>
                    <a href="#">Characters</a>
                </li>
                <li>
                    <a class="active" href="#">Comics</a>
                </li>
                <li>
                    <a href="#">Movies</a>
                </li>
                <li>
                    <a href="#">TV</a>
                </li>
                <li>
                    <a href="#">Games</a>
                </li>
                <li>
                    <a href="#">Collectibles</a>
                </li>
                <li>
                    <a href="#">Videos</a>
                </li>
                <li>
                    <a href="#">Fans</a>
                </li>
                <li>
                    <a href="#">News</a>
                </li>
                <li>
                    <a href="#">Shop</a>
                </li>
            </ul>
        </div>
</header>
</template>

<script>
    export default {
        
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
    }
    
</style>