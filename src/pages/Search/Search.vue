<template>
   <section class="search">
     <HeaderTop title="搜索"/>
     <form class="search_form" action="#">
       <input type="search" name="search" placeholder="请输入商家或美食名称">
       <input type="submit" name="submit" class="search_submit"
     </form>
   </section>
</template>

<script>
  import HeaderTop from '../../components/HeaderTop/HeaderTop.vue'
  export default {
    components: {
      HeaderTop
    }
  }
</script>

<style scoped lang="stylus" rel="stylesheet/stylus">
  @import "../../common/stylus/mixins.styl"
    .search //搜索
     width 100%
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

     .search_form
     clearFix()
     margin-top 45px
     background-color #fff
     padding 12px 8px
     input
       height 35px
       padding 0 4px
       border-radius 2px
       font-weight bold

</style>
