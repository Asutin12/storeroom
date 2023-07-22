<template>
    <div class="recruit__top">
        <Recruit />
    </div>
</template>
<script>
import Recruit from '@/components/templates/Recruit'

export default {
    components:{
        Recruit
    }
}
</script>
<style lang="scss" scoped>
.recruit__top {
    padding-block: 64px;
    background-color: #f5f5f5;
}
</style>