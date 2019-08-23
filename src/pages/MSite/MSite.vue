<template>
    <section class="msite">
<!--      首页头部-->
      <HeaderTop title="昌平北地地址">
         <span class="header_search" slot="left">
    <i class="iconfont icon-sousuo"></i>
  </span>
        <span class="header_login" slot="right">
  <span class="header_login_text">登录|注册</span>
    </span>
      </HeaderTop>
<!--      首页导航-->
      <nav class="msite_nav">
        <div class="swiper-container">
        <div class="swiper-wrapper">
        <div class="swiper-slide">
          <a href="javascript:" class="link_to_food">
            <div class="food_container">
              <img src="./images/nav/1.jpg">
            </div>
            <span>甜品饮品</span>
          </a>
          <a href="javascript:" class="link_to_food">
            <div class="food_container">
              <img src="./images/nav/2.jpg">
            </div>
            <span>商超便利</span>
          </a>
          <a href="javascript:" class="link_to_food">
            <div class="food_container">
              <img src="./images/nav/3.jpg">
        </div>
            <span>美食</span>
          </a>
          <a href="javascript:" class="link_to_food">
            <div class="food_container">
              <img src="./images/nav/4.jpg">
        </div>
            <span>简餐</span>
          </a>
          <a href="javascript:" class="link_to_food">
            <div class="food_container">
              <img src="./images/nav/5.jpg">
        </div>
            <span>新店特惠</span>
          </a>
          <a href="javascript:" class="link_to_food">
            <div class="food_container">
              <img src="./images/nav/6.jpg">
        </div>
            <span>准时达</span>
          </a> <a href="javascript:" class="link_to_food">
            <div class="food_container">
              <img src="./images/nav/7.jpg">
        </div>
            <span>预订早餐</span>
          </a> <a href="javascript:" class="link_to_food">
            <div class="food_container">
              <img src="./images/nav/8.jpg">
        </div>
            <span>土豪推荐</span>
          </a>
        </div>
          <div class="swiper-slide">
            <a href="javascript:" class="link_to_food">
              <div class="food_container">
                <img src="./images/nav/9.jpg">
              </div>
              <span>甜品饮品</span>
            </a>
            <a href="javascript:" class="link_to_food">
              <div class="food_container">
                <img src="./images/nav/10.jpg">
              </div>
              <span>商超便利</span>
            </a>
            <a href="javascript:" class="link_to_food">
              <div class="food_container">
                <img src="./images/nav/11.jpg">
              </div>
              <span>美食</span>
            </a>
            <a href="javascript:" class="link_to_food">
              <div class="food_container">
                <img src="./images/nav/12.jpg">
              </div>
              <span>简餐</span>
            </a>
            <a href="javascript:" class="link_to_food">
              <div class="food_container">
                <img src="./images/nav/13.jpg">
              </div>
              <span>新店特惠</span>
            </a>
            <a href="javascript:" class="link_to_food">
              <div class="food_container">
                <img src="./images/nav/14.jpg">
              </div>
              <span>准时达</span>
            </a>
            <a href="javascript:" class="link_to_food">
              <div class="food_container">
                <img src="./images/nav/1.jpg">
              </div>
              <span>预订早餐</span>
            </a>
            <a href="javascript:" class="link_to_food">
              <div class="food_container">
                <img src="./images/nav/2.jpg">
              </div>
              <span>土豪推荐</span>
            </a>
          </div>
        </div>
<!--          Add Pagination-->
<div class="swiper-pagination"></div>
        </div>
      </nav>
<!--      首页附近商家-->
      <div class="msite_shop_list">
      <div class="shop_header">
        <ShopList/>
        <i class="iconfont icon-xuanxiang"></i>
        <span class="shop_header_title">附近商家</span>
      </div>
        <div class="shop_container">
          <ul class="shop_list">
            <li class="shop_li border-1px">
            <a>
              <div class="shop_left">
                <img class="shop_img" src="../../components/ShopList/images/shop/1.jpg">
              </div>
              <div class="shop_right">
                <section class="shop_detail_header">
    </section>
</template>

<script>

  import Swiper from 'swiper'
  import 'swiper/dist/css/swiper.min.css'

  import HeaderTop from '../../components/HeaderTop/HeaderTop.vue'
  import ShopList from '../../components/ShopList/ShopList.vue'
    export default {
    mounted () {
      // 创建一个Swiper实例对象, 来实现轮播
      new Swiper('.swiper-container', {
        loop: true, // 可以循环轮播
        // 如果需要分页器
        pagination: {
          el: '.swiper-pagination',
        },
      })
    },
    components: {
      HeaderTop,
      ShopList
    }
        name: "FootGuide"
    }
</script>

<style scoped lang="stylus" rel="stylesheet/stylus">
  @import "../../common/stylus/mixins.styl"
.msite  //首页
  width 100%


 .miste_nav



































  .msite_shop_list
   top-border-1px(#e4e4e4)
    margin-top 10px
  background #fff
  .shop_header
  padding 10px 10px 0
  .shop_icon
  margin-left 5px
  color #999
  .shop_header_title
  color #999
  font-size 14px
  line-height 20px
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
