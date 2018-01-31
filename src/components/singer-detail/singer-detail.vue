<template>
  <transition name="slide">
    <h1>hahah</h1>
  </transition>
</template>

<script type="text/ecmascript-6">
  export default {}
</script>

<style lang="stylus" scoped rel="stylesheet/stylus">
  .slide-enter-active, .slide-leave-active
    transition all 0.3s
  .slide-enter, .slide-leave-to
    transform translate3d(100%, 0, 0)
</style>

