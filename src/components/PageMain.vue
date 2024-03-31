<template>
    <div class="page-main container">
        <AppHeader>

        </AppHeader>
        <AppContentBlock1>

        </AppContentBlock1>

        <AppContentBlock2>

        </AppContentBlock2>

        <AppFooter>

        </AppFooter>
    </div>
</template>

<script>
import AppContentBlock1 from './AppContentBlock1.vue'
import AppContentBlock2 from './AppContentBlock2.vue'
import AppFooter from './AppFooter.vue'
import AppHeader from './AppHeader.vue'

export default {
  components: { AppHeader, AppFooter, AppContentBlock1, AppContentBlock2 },
    name: "PageMain"
}

</script>

<style scoped>
.page-main {
    background-color: #c0dbd9;
}
</style>