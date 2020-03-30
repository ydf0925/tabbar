<template>
  <div id="app">
    <router-view></router-view>
    <tab-bar>
      <tab-bar-item path="/home" styleColor="orange">
        <img slot="item-icon" src="~assets/img/home.svg" alt="">
        <img slot="activeditem-icon" src="~assets/img/activedHome.svg" alt="">
        <div slot="item-text">首页</div>
      </tab-bar-item>
      <tab-bar-item path="/category" styleColor="orange">
        <img slot="item-icon" src="~assets/img/category.svg" alt="">
        <img slot="activeditem-icon" src="~assets/img/activedCategory.svg" alt="">
        <div slot="item-text">分类</div>
      </tab-bar-item>
      <tab-bar-item path="/cart" styleColor="orange">
        <img slot="item-icon" src="~assets/img/cart.svg" alt="">
        <img slot="activeditem-icon" src="~assets/img/activedCart.svg" alt="">
        <div slot="item-text">购物车</div>
      </tab-bar-item>
      <tab-bar-item path="/profile" styleColor="orange">
        <img slot="item-icon" src="~assets/img/profile.svg" alt="">
        <img slot="activeditem-icon" src="~assets/img/activedProfile.svg" alt="">
        <div slot="item-text">我的</div>
      </tab-bar-item>
    </tab-bar>
  </div>
</template>

<script>
import TabBar from 'components/tabbar/TabBar'
import TabBarItem from 'components/tabbar/TabBarItem'
export default {
  name: 'App',
  components:{
    TabBar,
    TabBarItem
  }
}
</script>

<style>
@import "assets/css/base.css";


</style>
