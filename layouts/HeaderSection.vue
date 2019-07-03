<template>
    <header>
        <headerlayer-art />
        <div class="top-bar">
            <logo />
            <div class="spacing"/>
            <v-button>Free download</v-button>
        </div>
        <div class="text-section">
            <h1>Product Analytics</h1>
        <h1>explained</h1>
        <p>There are many variations of passages of Lorem Ipsum available, but the majority have suffered alteration in some form, by injected humour</p>
        <div class="search-section">
            <v-input placeholder="name@example.com"/>
            <v-button>Try for free</v-button>
        </div>
        </div>
        <header-chart-art />
    </header>
</template>
<script>
import HeaderlayerArt from '../components/art/HeaderlayerArt'
import HeaderChartArt from '../components/art/HeaderChartArt'
import Logo from '../components/Logo'
import VButton from '../components/Button'
import VInput from '../components/Input'
export default {
    components:{
        HeaderlayerArt,
        HeaderChartArt,
        Logo,
        VButton,
        VInput
    }
}
</script>
<style lang="stylus">
header
    position relative
    .text-section
        margin-top 100px
        h1
            position relative
            text-align center
            color white
            font-weight bold
            font-size 3rem
            margin 0
        p
            max-width 40%
            position relative
            display block
            margin 36px auto
            color rgba(white,0.7)
            z-index 1
            text-align center
    .top-bar
        padding 1rem 8rem
        display flex
        align-items center     
        .spacing
            flex-grow 1       
        button
            position relative
    .search-section
        display flex
        position relative
        justify-content center
        z-index 10
        button 
            color black 
            background #ffe700 !important
            margin 0 10px
</style>
