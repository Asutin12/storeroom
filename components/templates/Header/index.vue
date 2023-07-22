<template>
    <div class="header">
        <div class="header__global-nav">
            <div class="header__global-nav__title">合同会社優飛</div>
            <ul class="header__global-nav__list">
                <li class="header__global-nav__item">事業内容</li>
                <li class="header__global-nav__item">企業情報</li>
                <li class="header__global-nav__item">カタログ</li>
            </ul>
        </div>
        <button class="header__button">採用情報</button>
    </div>
</template>
<script>
</script>
<style lang="scss" scoped>
.header {
    padding-block: 16px;
    background-color: #f5f5f5;
    color: #1f1f1f;
    display: flex;
    justify-content: space-between;
    padding-inline: 24px;
    align-items: center;
    &__global-nav {
        width: 400px;
        justify-content: space-between;
        display: flex;
        align-items: center;
        &__list {
            width: 240px;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }
    }
    &__button {
        width: auto;
        background-color: #096fca;
        border-color: #096fca;
        color: #f5f5f5;
        border-radius: 48px;
        padding: 8px 38px;
        font-size: 16px;
        &:hover {
            background-color: #f5f5f5;
            border-color: #096fca;
            color: #096fca;
            transition: .5s;
        }
    }
}
</style>