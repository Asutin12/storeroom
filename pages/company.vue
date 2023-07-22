<template>
    <div class="company">
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
.company {
    padding-block: 64px;
    background-color: #f5f5f5;
}
</style>