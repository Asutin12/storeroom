<template>
    <div class="footer">
        <ul class="footer__list">
            <li class="footer__item">
                <NuxtLink class="link" to="/business">
                    事業内容
                </NuxtLink>
            </li>
            <li class="footer__item">
                <NuxtLink class="link" to="/company">
                    企業情報
                </NuxtLink>
            </li>
            <li class="footer__item">
                <NuxtLink class="link" to="/">
                    カタログ
                </NuxtLink>
            </li>
            <li class="footer__item">
                <NuxtLink class="link" to="/recruit">
                    採用情報
                </NuxtLink>
            </li>
        </ul>
        <hr class="footer__horizontalline">
        <div class="footer__copyright">
            <p>Copyright &copy; yuuhi,LLC.All Rights Reserved.</p>
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
.link {
    text-decoration: none;
    color: #1f1f1f;
    font-weight: bold;
    &:hover {
        color: #096fca;
        transition: .5s;

    }
}
</style>