<template>
    <div class="comapnies-section">
        <div class="company-row">
            <div class="company-item">
                <img src="../static/img/cartoon_network.png" alt="Cartoon Network" />
            </div>
            <div class="company-item">
                <img src="../static/img/booking.com.png" alt="Booking.com" />
            </div>
            <div class="company-item">
                <img src="../static/img/dropbox.png" alt="Dropbox" />
            </div>
            <div class="company-item">
                <img src="../static/img/slack.png" alt="Slack" />
            </div>
        </div>
        <div class="company-row">
            <div class="company-item">
                <img src="../static/img/toshiba.png" alt="Toshiba" />
            </div>
            <div class="company-item">
                <img src="../static/img/spotify.png" alt="Spotify" />
            </div>
            <div class="company-item">
                <img src="../static/img/coca_cola.png" alt="Coca Cola" />
            </div>
            <div class="company-item">
                <img src="../static/img/netflix.png" alt="Netflix" />
            </div>
        </div>
    </div>
</template>
<style lang="stylus">
.comapnies-section
    margin-top 90vh
    .company-row
        position relative
        z-index 10
        display flex
        overflow-y auto
        justify-content center
        .company-item
            img
                height 32px
                width auto
                margin 20px
</style>
