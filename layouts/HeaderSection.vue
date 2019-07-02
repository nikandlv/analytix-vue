<template>
    <header>
        <headerlayer-art />
        <div class="top-bar">
            <logo />
            <div class="spacing"/>
            <button>Free download</button>
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
    .top-bar
        padding 1rem 8rem
        display flex
        align-items center     
        .spacing
            flex-grow 1       
        button
            position relative
</style>
