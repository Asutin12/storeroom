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
            <p>Copyright &copy; yuuhi,LLCLLC.All Rights Reserved.</p>
        </div>
    </div>
</template>
<script>
</script>
<style lang="scss" scoped>
.footer {
    color: #1f1f1f;
    width: 100%;
    height: 100px;
    background-color: #f5f5f5;
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
        color: #1f1f1f;
    }
    &__copyright {
        margin-inline: auto;
        text-align: center;
        margin-block: 8px;
    }
}
</style>