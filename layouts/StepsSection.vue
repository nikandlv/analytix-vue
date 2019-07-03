<template>
    <div class="steps-section">
        <div class="title-section">
            <h1>Break down, measure, and improve your client experience. Again and again.</h1>
            <div class="tabs">
                <span v-on:click="tab=0" :class="tab === 0?'tab active':'tab'" class="tab">Collect accurate data</span>
                <span v-on:click="tab=1" :class="tab === 1?'tab active':'tab'" class="tab">Identify trends</span>
                <span v-on:click="tab=2" :class="tab === 2?'tab active':'tab'" class="tab">Understand the reason</span>
                <span v-on:click="tab=3" :class="tab === 3?'tab active':'tab'">Set goals and Hypothesis</span>
            </div>
        </div>
        <div class="content-section">
            <div class="text-section">
                <h2>Why do you need task management software?</h2>
                <p>Do you waste time organizing sticky notes, searching your email and apps for todos and figuring out what to work on first? Then you need one solution to prioritize your tasks, manage your time and meet your deadlines.</p>
                <a href="#">Learn More</a>
            </div>
            <steps-art />
        </div>
    </div>
</template>
<script>
import StepsArt from '../components/art/StepsArt'
export default {
    components:{
        StepsArt
    },
    data:function() {
        return {
            tab:3
        }
    }
}
</script>

<style lang="stylus">
.steps-section
    margin-top 35%
    position relative
    z-index 12
    .title-section
        max-width 50%
        margin 0 auto
        color lighten(black,30)
    .tabs
        display flex
        margin 24px 0
        overflow-y auto
        .tab
            transition border-bottom-color  500ms
            padding 10px
            margin 0
            border-bottom 2px solid rgba(black,0.1)
            font-size 0.9rem
            cursor pointer
            &.active
                border-bottom 2px solid #73a9ff
    .content-section
        display flex
        padding 0 16vw
        align-items center
        .text-section
            max-width 50%
            h2
                max-width 50%
                color darken(#637eab,20)
            p
                color #637eab
                margin 40px 0
            a
                font-weight bold
                color darken(#637eab,20)
                text-decoration none
@media (max-width 1000px)
    .steps-section
        margin-top 100%
    .title-section
        max-width 90% !important
    .content-section
        padding 0 1vw !important
        flex-direction column
        .text-section
            max-width 100% !important
            h2
                max-width 100% !important
</style>
