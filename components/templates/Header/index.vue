<template>
    <div class="header">
        <div class="header__global-nav">
            <div class="header__global-nav__title">合同会社優飛</div>
            <ul class="header__global-nav__list">
                <li class="header__global-nav__item">事業内容</li>
                <li class="header__global-nav__item">会社概要</li>
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
    height: 64px;
    background-color: gray;
    color: #fff;
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
        width: 80px;
        height: 32px;
        background: #fff;
        color: gray;
        border-radius: 20px;
    }
}
</style>