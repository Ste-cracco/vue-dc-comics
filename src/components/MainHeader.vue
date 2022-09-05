<template>
   <header class="container">
        <div class="logo">
            <img src="../assets/img/dc-logo.png" alt="Logo">
        </div>
        <ul class="menu">
            <li>Characters
                <a href="#"></a>
            </li>
            <li class="active">Comics
                <a href="#"></a>
            </li>
            <li>Movies
                <a href="#"></a>
            </li>
            <li>TV
                <a href="#"></a>
            </li>
            <li>Games
                <a href="#"></a>
            </li>
            <li>Collectibles
                <a href="#"></a>
            </li>
            <li>Videos
                <a href="#"></a>
            </li>
            <li>Fans
                <a href="#"></a>
            </li>
            <li>News
                <a href="#"></a>
            </li>
            <li>Shop
                <a href="#"></a>
            </li>
        </ul>
</header>
</template>

<script>
    export default {
        
    }
</script>

<style lang="scss" scoped>

    .container {
        display: flex; 
        
        .logo {
            padding: 20px
        }

        img {
            height: 85px;
        }

        ul {
            display: flex;
            line-height: 125px;
            text-transform: uppercase;
            margin-left: auto;
            gap: 25px;
        }

        li {
            font-weight: bold;
            color: #464646;
            font-size: 14px;

            &.active, &.hover {
                border-bottom: 5px solid #0282F9;
                color: #0282F9;;
                
            }
        }
    }
</style>