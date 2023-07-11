<template>
    <div class="footer">
        <ul class="footer__list">
            <li class="footer__item">事業内容</li>
            <li class="footer__item">企業情報</li>
            <li class="footer__item">カタログ</li>
            <li class="footer__item">採用情報</li>
        </ul>
        <hr class="footer__horizontalline">
        <div class="footer__copyright">
            <p>Copyright &copy; yuuhi,inc.All Rights Reserved.</p>
        </div>
    </div>
</template>
<script>
</script>
<style lang="scss" scoped>
.footer {
    color: #fff;
    width: 100%;
    height: 100px;
    background-color: gray;
    padding-inline: 24px;
    &__list {
        width: 328px;
        height: 59px;
        display: flex;
        align-items: center;
        justify-content: space-between;
        list-style: none;
        margin-left: 80px;
    }
    &__horizontalline {
        color: #fff;
    }
    &__copyright {
        margin-inline: auto;
        text-align: center;
        margin-block: 8px;
    }
}
</style>