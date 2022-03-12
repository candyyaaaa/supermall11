<template>
   <TabBar>
     <TabBArItem path="/home">
       <img slot="item-icon" src="~assets/img/tabbar/home.png" />
       <img slot="item-icon-active" src="~assets/img/tabbar/home-active.png" />
       <div slot="item-text">首页</div>
       <!-- <template v-slot:item-text>
        <div>首页</div>
       </template> 注：这种方法也可以为item-text提供文本内容，与上面效果一样 -->
     </TabBArItem>
     <TabBArItem path="/category">
       <img slot="item-icon" src="~assets/img/tabbar/category.png" />
       <img slot="item-icon-active" src="~assets/img/tabbar/category_active.png" />
       <div slot="item-text">分类</div>
     </TabBArItem>
     <TabBArItem path="/shopcart">
       <img slot="item-icon" src="~assets/img/tabbar/shopcart.png" />
       <img slot="item-icon-active" src="~assets/img/tabbar/shopcart_active.png" />
       <div slot="item-text">购物车</div>
     </TabBArItem>
     <TabBArItem path="/profile">
       <img slot="item-icon" src="~assets/img/tabbar/profile.png" />
       <img slot="item-icon-active" src="~assets/img/tabbar/profile_active.png" />
       <div slot="item-text">分类</div>
     </TabBArItem>

   </TabBar>
</template>

<script>
  import TabBar from 'components/common/tabbar/TabBar.vue'
  import TabBArItem from 'components/common/tabbar/TabBarItem.vue'
  export default {
    name: 'App',
    components: {
      TabBar,
      TabBArItem
    }
  }
</script>

<style>
</style>
