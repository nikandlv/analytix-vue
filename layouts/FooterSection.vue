<template>
    <footer>
        <footer-art />
        <div class="content">
            <h1>Get better work done</h1>
            <p>See why millions of people across 190 countries use Analytix</p>
            <div class="input">
                <v-input placeholder="example@nikandlv.ir" />
                <v-button>Try for free</v-button>
            </div>
        </div>
    </footer>
</template>
<script>
import FooterArt from '../components/art/FooterArt'
import VButton from '../components/Button'
import VInput from '../components/Input'
export default {
    components:{
        FooterArt,
        VButton,
        VInput
    }
}
</script>
<style lang="stylus">
footer
    margin-top 100px
    padding 4rem
    position relative
    display flex
    .content
        max-width 40%
        display block
        margin 0 auto 
        margin-top 100px
        position relative
        text-align center
        z-index 10
        h1
            color white
        p
            color rgba(white,0.7)
        .input
            margin-top 60px
            display flex
            align-items center
            justify-content  center
            ::placeholder
                color: lighten(black,35)
                opacity: 1; /* Firefox */

            :-ms-input-placeholder
                color: lighten(black,35)

            ::-ms-input-placeholder
                color: lighten(black,35)
            input 
                background rgba(white,0.2)
                border 2px solid white

            button 
                margin 0 10px
                padding 1rem 1.5rem
</style>
