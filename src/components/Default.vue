<template>
<!--    <Header/>-->

    <Game/>

<!--    <Footer/>-->
</template>

<script>
    import Game from '@/components/Game.vue';
    import Header from '@/components/Header'
    import Footer from '@/components/Footer'

    export default {
        name: 'Default',
        components: {
            Header, Footer, Game
        }
    }
</script>

<style lang="scss">
    .footer{
        background-color: #5dbaff;
    }
</style>
