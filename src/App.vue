<template>
  <div>
    <MainHeader/>
    <MainContent/>
    <MainFooter/>
  </div>
</template>

<script>
import MainHeader from './components/MainHeader.vue'
import MainContent from './components/MainContent.vue'
import MainFooter from './components/MainFooter.vue'

export default {
  name: 'App',
  components: {
    MainHeader,
    MainContent,
    MainFooter
  }
}
</script>

<style lang="scss">
  *{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: Arial, Helvetica, sans-serif;
  }
  ul,ol,menu {
    list-style: none;
  }
  img {
    max-width: 100%;
  }

  .container {
    max-width: 1200px;
    margin: auto;
  }
</style>
