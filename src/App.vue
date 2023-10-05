<script>
import AppHeader from './components/AppHeader.vue';
import AppMain from './components/AppMain.vue';
import AppFooter from './components/AppFooter.vue';
import { headerData } from './headerData.js'
import { footerData } from './footerData.js'

export default {
    data() {
        return {
            headerData,
            footerData
        }
    },
    components: {
      AppHeader,
      AppMain,
      AppFooter
    },
};

</script>

<template>
  <AppHeader :menu="this.headerData"></AppHeader>
  <AppMain></AppMain>
  <AppFooter :post="this.footerData"></AppFooter>
</template>

<style scoped>

</style>
