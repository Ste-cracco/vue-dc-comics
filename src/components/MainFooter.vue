<template>
    <footer>
        <div class="footer_top">
            <div class="container_footer_top">
                <div class="card">
                    <img src="../assets/img/buy-comics-digital-comics.png" alt="">
                    <h4>Digital Comics</h4>
                </div>
                <div class="card">
                    <img src="../assets/img/buy-comics-merchandise.png" alt="">
                    <h4>DC Merchandise</h4>
                </div>
                <div class="card">
                    <img src="../assets/img/buy-comics-subscriptions.png" alt="">
                    <h4>Subcription</h4>
                </div>
                <div class="card">
                    <img src="../assets/img/buy-comics-shop-locator.png" alt="">
                    <h4>Comic Shop Locator</h4>
                </div>
                <div class="card">
                    <img src="../assets/img/buy-dc-power-visa.svg" alt="">
                    <h4>DC Power Visa</h4>
                </div>
            </div> <!-- Chiusura Container Footer Top -->
        </div> <!-- Chiusura Footer Top -->

            <div class="footer_middle">
                <div class="container_footer_middle">
                    <MenuFooter :links="menu"/>
                    <div class="logo_footer">
                        <img src="../assets/img/dc-logo-bg.png" alt="Logo footer">
                    </div>
                </div> <!-- Chiusura Container Footer middle -->
            </div> <!-- Chiusura Footer middle -->

            <div class="footer_bottom">
                <div class="container_footer_bottom">
                    <div class="bottone">
                        <button>Sign Up Now!</button>
                    </div>
                    <div class="container_social">
                        <span>Follow Us</span>
                        <img src="../assets/img/footer-facebook.png" alt="">
                        <img src="../assets/img/footer-twitter.png" alt="">
                        <img src="../assets/img/footer-youtube.png" alt="">
                        <img src="../assets/img/footer-periscope.png" alt="">
                        <img src="../assets/img/footer-pinterest.png" alt="">
                    </div>
                </div>    
            </div> <!-- Chiusura Footer bottom -->        
    </footer>
</template>

<script>
import MenuFooter from './MenuFooter.vue'

    export default {
    components: { MenuFooter },
        data() {
            return {
                menu: [
                    {
                        testo: 'DC Comics',
                        href: '#',
                        title: true
                    },
                    {
                        testo: 'Lorem1',
                        href: '#',
                        title: false
                    },
                    {
                        testo: 'Lorem2',
                        href: '#',
                        title: false
                    },
                    {
                        testo: 'Lorem3',
                        href: '#',
                        title: false
                    },
                    {
                        testo: 'Characters',
                        href: '#',
                        title: false
                    },
                    {
                        testo: 'Characters',
                        href: '#',
                        title: false
                    },
                    {
                        testo: 'Characters',
                        href: '#',
                        title: false
                    },     
                    {
                        testo: 'Characters',
                        href: '#',
                        title: false
                    },    
                    {
                        testo: 'Shop',
                        href: '#',
                        title: true
                    },   
                    {
                        testo: 'Characters',
                        href: '#',
                        title: false
                    },    
                    {
                        testo: 'Characters',
                        href: '#',
                        title: false
                    },                    
                ]
            }
        }
    }
</script>

<style lang="scss" scoped >

    @import '../style/footer_top.scss';
    @import '../style/footer_middle.scss';
    @import '../style/footer_bottom.scss';  

</style>