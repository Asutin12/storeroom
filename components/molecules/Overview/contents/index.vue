<template>
    <div class="content">
        <h3 class="content__category">{{ content.category }}</h3>
        <p class="content__item">{{ content.item }}</p>
    </div>
</template>
<script>
export default {
    props: {
        content:{
            type: Object
        }
    }
}
</script>
<style lang="scss" scoped>
.content {
    display: flex;
    align-items: center;
    border-bottom: 1px solid #000000;
    padding-bottom: 16px;
    margin-top: 32px;
    &__category {
        width: 150px;
    }
    &__item {
        margin-left: 64px;
    }
}
</style>