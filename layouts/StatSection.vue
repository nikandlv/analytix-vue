<template>
    <div class="stat-root">
        <h1>The key questions answered by</h1>
        <h1>Product Analytics</h1>
        <div class="stat-section">
            <stat-card>
                <template v-slot:increase>$300K</template>
                <template v-slot:title>saved annually</template>
                tracking tasks allows everyone to understand which are more important or require more time
            </stat-card>
            <stat-card>
                <template v-slot:increase>5%</template>
                <template v-slot:title>profit increment</template>
                tracking tasks allows everyone to understand which are more important or require more time
            </stat-card>
            <stat-card>
                <template v-slot:increase>400%</template>
                <template v-slot:title>developmenmt efficiency</template>
                tracking tasks allows everyone to understand which are more important or require more time
            </stat-card>
        </div>
    </div>
</template>
<script>
import StatCard from '../components/StatCard'
export default {
    components:{
        StatCard
    }
}
</script>

<style lang="stylus">
.stat-root
    margin-top 100px
    h1
        text-align center
        color darken(#637eab,20)
.stat-section
    display flex
    flex-direction row-reverse
    justify-content center
    overflow-y auto
@media (max-width 1000px)
    .stat-section
        flex-direction column-reverse
        align-items center
</style>
