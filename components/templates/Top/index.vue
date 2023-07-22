<template>
    <div class="top">
        <CompanyOverView />
    </div>
</template>
<script>
import CompanyOverView from '@/components/organisms/CompanyOverView'

export default {
    components: {
        CompanyOverView
    }
}
</script>
<style lang="scss" scoped>
.top {
    padding-block: 32px;
    background-color: #f5f5f5;
}
</style>