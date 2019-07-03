<template>
    <button>
        <slot>Button</slot>
    </button>
</template>
<style lang="stylus">
button
    background-color rgba(white,0.3)
    color white
    -webkit-box-shadow: 0px 13px 26px -16px rgba(0,0,0,0.41);
    -moz-box-shadow: 0px 13px 26px -16px rgba(0,0,0,0.41);
    box-shadow: 0px 13px 26px -16px rgba(0,0,0,0.41);
    outline none 
    border unset
    padding 0.6rem 1.5rem
    font-size 0.8rem
    border-radius 1000px
    cursor pointer
    transition box-shadow 400ms, background-color 200ms
    &:hover
        box-shadow 0px 4px 5px 0px rgba(0,0,0,0.0.4), 0px 4px 2px 0px rgba(0,0,0,0.06), 0px 3px 1px -2px rgba(0,0,0,0.06)
        background-color rgba(white,0.6)
</style>
