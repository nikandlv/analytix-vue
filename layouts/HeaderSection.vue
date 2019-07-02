<template>
    <header>
        <headerlayer-art />
        <div class="top-bar">
            <logo />
            <div class="spacing"/>
            <button>Free download</button>
        </div>
        <div class="text-section">
            <h1>Product Analytics</h1>
        <h1>explained</h1>
        <p>There are many variations of passages of Lorem Ipsum available, but the majority have suffered alteration in some form, by injected humour</p>
        </div>
    </header>
</template>
<script>
import HeaderlayerArt from '../components/art/HeaderlayerArt'
import Logo from '../components/Logo'
import Button from '../components/Button'
export default {
    components:{
        HeaderlayerArt,
        Logo,
        Button
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
</style>
