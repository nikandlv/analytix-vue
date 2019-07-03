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
    </div>
</template>
<script>
export default {
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
        .tab
            transition border-bottom-color  500ms
            padding 10px
            margin 0
            border-bottom 2px solid rgba(black,0.1)
            font-size 0.9rem
            cursor pointer
            &.active
                border-bottom 2px solid #73a9ff
</style>
