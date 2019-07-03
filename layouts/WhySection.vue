<template>
    <div class="why-section">
        <why-layer-art />
        <div class="content">
            <div class="text-section">
                <h1>Why do you need task management software?</h1>
                <p>Do you waste time organizing sticky notes, searching your email and apps for todos and figuring out what to work on first? Then you need one solution to prioritize your tasks, manage your time and meet your deadlines.</p>
                <a href="#">Learn More</a>
            </div>
            <why-art />
        </div>
    </div>
</template>
<script>
import WhyLayerArt from '../components/art/WhyLayerArt'
import WhyArt from '../components/art/WhyArt'
export default {
    components:{
        WhyLayerArt,
        WhyArt
    }
}
</script>

<style lang="stylus">
.why-section
    margin-top 100px
    position relative
    z-index 10
    display flex
    .content
        position relative
        z-index 10
        display flex
        margin unset
        margin-top 50%
        .text-section
            max-width 40%
            position relative
            z-index 10
            margin-left 12rem
            h1
                color white
            p
                color rgba(white,0.8)
            a
                font-weight bold
                color white
                margin 10px 0
                text-decoration none
@media (max-width 1000px)
    .text-section
        max-width 100% !important
        margin-left 0rem !important
        background white
        padding 1rem
        box-sizing border-box
</style>
