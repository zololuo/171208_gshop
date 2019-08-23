<template>
  <header class="header">
  <slot name="left"></slot>
    <span class="header_title">
  <span class="header_title_text ellipsis">{{title}}</span>
    </span>
    <slot name="right"></slot>
  </header>
</template>

<script>
    export default {
      props: {
        title: String
      }
        name: "HeaderTop"
    }
</script>

<style scoped lang="stylus" rel="stylesheet/stylus">
  .header
    background-color #02a774
    position fixed
    z-index 100
    left 0
    top 0
    width 100%
    height 45px
  .header_search
  position absolute
  left 15px
</style>
