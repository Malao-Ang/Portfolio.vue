<template>
    <html>
        <portpage/>
        <router-view></router-view>
    </html>
</template>

<script>
import portpage from '@/components/PortPage.vue'
export default {
    name:'PortPage',
    components: {
        portpage
    }

}
</script>

<style>

</style>