<template>
    <div class="stat-card">
        <p class="increase"><slot name="increase">0%</slot></p>
        <p class="title"><slot name="title">This is the stat</slot></p>
        <p class="description"><slot>...</slot></p>
        <svg xmlns="http://www.w3.org/2000/svg" class="art" xmlns:xlink="http://www.w3.org/1999/xlink" width="286.24" height="234.814" viewBox="0 0 286.24 234.814">
        <defs>
            <linearGradient id="linear-gradient" x1="0.526" y1="0.23" x2="2.173" y2="0.407" gradientUnits="objectBoundingBox">
            <stop offset="0" stop-color="#1771ff"/>
            <stop offset="1" stop-color="#ffe601"/>
            </linearGradient>
        </defs>
        <path id="Path_378" data-name="Path 378" d="M52.759,2.909,242.282,30.073,187.741,141.9,80.166,106.4C28.124,89.916-15.983,61.728-7.3,34.808S10.509,2.909,52.759,2.909Z" transform="matrix(0.899, -0.438, 0.438, 0.899, 6.274, 103.594)" opacity="0.12" fill="url(#linear-gradient)"/>
        </svg>

    </div>
</template>
<style lang="stylus">
.stat-card
    padding 2rem
    min-width 200px
    max-width 200px
    margin 15px
    box-shadow 0px 13px 40px -12px rgba(#73a9ff,0)
    position relative
    transition box-shadow 300ms
    background white
    &:hover
        box-shadow 0px 13px 40px -12px rgba(#73a9ff,0.41)
        .art
            opacity 1
    p
        margin 0
        text-align center
    .increase
        color #73a9ff
        font-weight bold
        margin-top 30px
        font-size 2rem
    .title
        font-weight bold
        font-size 1rem
        margin 15px 0
        color lighten(black,30)
        text-transform lowercase
    .description
        color lighten(black,50)
        font-size 0.9rem
    .art
        opacity 0
        position absolute
        top  0
        right  -32px
        max-width  100%
        width  70%
        height  auto
        transition opacity 400ms
</style>
