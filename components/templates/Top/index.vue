<template>
    <div class="top">
        <mainView />
        <AchievementSection />
        <CompanyOverView />
    </div>
</template>
<script>
import CompanyOverView from '@/components/organisms/CompanyOverView'
import mainView from '@/components/organisms/Top/main.vue'
import AchievementSection from '@/components/organisms/Top/Achievement.vue'

export default {
    components: {
        CompanyOverView,
        mainView,
        AchievementSection
    }
}
</script>
<style lang="scss" scoped>
.top {
    background-color: #f5f5f5;
}
</style>