<template lang="pug">
b-container
  appHeader
</template>

<script>
import appHeader from './components/HeaderFooter/AppHeader'
export default {
  components: {
    appHeader
  }
}
</script>

<style lang="sass">
#app
  padding-left: 0
  padding-right: 0
  display: flex
  flex-wrap: wrap
  justify-content: center
</style>
