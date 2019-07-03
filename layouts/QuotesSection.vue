<template>
    <div class="quotes-section">
        <h1 class="title">What clients are saying</h1>
        <div class="client">
            <div class="client-image">
                <img src="../static/img/ceo.jpg" alt="Client">
                <svg xmlns="http://www.w3.org/2000/svg" class="play-button" width="60" height="60" viewBox="0 0 60 60">
                    <path id="play-button" d="M30,0A30,30,0,1,0,60,30,30.034,30.034,0,0,0,30,0ZM45.563,30.826l-22,15A1,1,0,0,1,23,46a1,1,0,0,1-1-1V15a1,1,0,0,1,1.564-.826l22,15a1,1,0,0,1,0,1.652Z" fill="#fff"/>
                </svg>

            </div>
        </div>
    </div>
</template>
<style lang="stylus">
.quotes-section
    margin-top 100px
    h1
        color darken(#637eab,20)
        text-align center
    .client
        display flex
        justify-content center
        .client-image
            box-shadow 0px 13px 40px -0px rgba(#73a9ff,0.4)
            position relative
            &:before
                content ''
                position absolute
                right 0
                bottom 0
                width 50%
                height 30%
                border-top-left-radius 100px
                background rgba(#1771ff,0.7)
            img
                max-width 300px
                height auto
                display block
            .play-button
                position absolute
                right 13%
                width 36px
                bottom 7%
                
</style>
