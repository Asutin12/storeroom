<template>
    <div class="business__top">
        <Business />
    </div>
</template>
<script>
import Business from '@/components/templates/Business'

export default {
    components:{
        Business
    }
}
</script>
<style lang="scss" scoped>
.business__top {
    padding-block: 64px;
    background-color: #f5f5f5;
}
</style>