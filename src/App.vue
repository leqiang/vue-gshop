<template>
  <div>
    <router-view/>
    <FooterGuide v-if="$route.meta.showFooter"/>
  </div>
</template>

<script>

import FooterGuide from './components/FooterGuide/FooterGuide'

export default {
  data(){
    return {

    }
  },
  components: {
    FooterGuide
  }

}
</script>

<style lang="stylus" rel="stylesheet/stylus">


</style>
