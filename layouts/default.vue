<template>
    <div>
        <Header />
        <nuxt />
        <Footer />
    </div>
</template>
<script>
import Header from '@/components/templates/Header'
import Footer from '@/components/templates/Footer'


export default {
    components:{
        Header,
        Footer
    }
}
</script>