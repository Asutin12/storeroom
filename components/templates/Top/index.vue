<template>
    <div class="top">
        <mainView />
        <AchievementSection />
    </div>
</template>
<script>
import mainView from '@/components/organisms/Top/main.vue'
import AchievementSection from '@/components/organisms/Top/Achievement.vue'

export default {
    components: {
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