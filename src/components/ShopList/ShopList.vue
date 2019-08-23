<template>
<!--  <section class="msite">-->
<!--    &lt;!&ndash;    首页导航&ndash;&gt;-->
<!--    <nav class="msite_nav">-->
      <div class="swiper-container">
        <ul class="shop_list">
        <li class="shop_li border-1px">
          <a>
            <div class="shop_left">
              <img class="shop_img" src="./images/shop/1.jpg">
            </div>
            <div class="shop_right">
              <section class="shop_detail_header">
              <h4 class="shop_title ellipsis">锄条日当午
              </h4>
              <ul class="shop_detail_ul">
                <li class="supports">保</li>
                <li class="supports">准</li>
                <li class="supports">票</li>
              </ul>
              </section>
<section class="shop_rating_order">
<section class="shop_rating_order_left">
  <div class="star star-24">
    <span class="star-item on"></span>
    <span class="star-item on"></span>

</section>
            </div>
          </a>

        </li>
<!--        <div class="swiper-wrapper">-->
<!--          <div class="swiper-slide">-->
<!--            <div class="swiper-slide">-->
<!--    </nav>-->
<!--    &lt;!&ndash;  首页附近商家&ndash;&gt;-->
<!--    <div class="msite_shop_list">-->
<!--  </section>-->
</template>


<script>
    export default {
        name: "ShopList"
    }
</script>

<style scoped lang="stylus" rel="stylesheet/stylus">
  @import "../../common/stylus/mixins.styl"
  .shop_container
    margin-bottom 50px
  .shop_list
  .shop_li
  bottom-border-1px(#f1f1f1)
  width 100%
  >a
  clearFix()
  display block
  box-sizing border-box
  padding 15px 8px
  width 100%

</style>
