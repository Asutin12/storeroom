<template>
    <div class="list">
        <Contents v-for="content of contents" :key="content.id" :content="content" />
    </div>
</template>
<script>
import Contents from '@/components/molecules/Overview/contents'

export default {
    components: {
        Contents
    },
    data() {
        return {
            contents: [
                {
                    category: '社名',
                    item: '株式会社 山田建設'
                },
                {
                    category:'設立',
                    item: '2000年12月12日'
                },
                {
                    category:'事業内容',
                    item: 'hogehogehoge'
                },
                {
                    category:'代表者名',
                    item: 'hogehogehoge'
                },
                {
                    category:'事務所所在地',
                    item: 'hogehogehoge'
                }
            ]
        }
    }
}
</script>
<style lang="scss" scoped>
</style>