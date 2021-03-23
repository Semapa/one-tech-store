<template>
  <div class="header">
    <the-top-bar />
    <the-header-main />
  </div>
  <router-view /> 
  <the-footer />
</template>

<script>
import TheTopBar from '@/components/TheTopBar'
import TheHeaderMain from '@/components/TheHeaderMain'
import TheFooter from '@/components/TheFooter'

export default {
  components: {TheTopBar, TheHeaderMain, TheFooter}
}
</script>

<style scoped>

</style>