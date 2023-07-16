<template>
    <div class="overview">
        <img class="overview__title" src="../../../assets/images/overview/title.svg" alt="CompanyOverview">
        <div>
            <img class="overview__subtitle" src="../../../assets/images/overview/subtitle.svg" alt="subTitle">
            <div class="overview__contents">
                <ContentsList />
            </div>
        </div>
    </div>
</template>
<script>
import ContentsList from '@/components/molecules/Overview/contentsList'

export default {
    components: {
        ContentsList
    }
}
</script>
<style lang="scss" scoped>
.overview {
    max-width: 1200px;
    margin-inline: auto;
    &__title {
        margin-inline: auto;
        margin-bottom: 80px;
    }
    &__subtitle {
        padding-bottom: 80px;
    }
    &__contents {
        float: right;
        width: 720px;
    }
}
</style>