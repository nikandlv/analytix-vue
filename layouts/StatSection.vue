<template>
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
.stat-section
    margin-top 60px
    display flex
    flex-direction row-reverse
    justify-content center
    overflow-y auto
</style>
