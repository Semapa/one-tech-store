<template>
  <div class="header">
    <the-top-bar />
    <the-header-main />
    <!-- <the-navbar /> -->
  </div>
  <router-view /> 
</template>

<script>
// import TheNavbar from '@/components/TheNavbar'
import TheTopBar from '@/components/TheTopBar'
import TheHeaderMain from '@/components/TheHeaderMain'

export default {
  components: {TheTopBar, TheHeaderMain}
}
</script>

<style scoped>

</style>