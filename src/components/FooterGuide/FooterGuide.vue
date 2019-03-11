<template>
    <footer class="footer_guide">
      <a href="javascript:;" class="guide_item" :class="{on: $route.path==='./msite'}" @click="goTo('/msite')">
        <span class="item_icon">
          <i class="iconfont icon-icon_home"></i>
        </span>
        <span>首页</span>
      </a>
      <a href="javascript:;" class="guide_item" :class="{on: $route.path==='./cate'}" @click="goTo('/cate')">
        <span class="item_icon">
          <i class="iconfont icon-category"></i>
        </span>
        <span>分类</span>
      </a>
      <a  href="javascript:;" class="guide_item" :class="{on: $route.path==='./sesrch'}" @click="goTo('/search')">
        <span class="item_icon">
          <i class="iconfont icon-topic"></i>
        </span>
        <span>识物</span>
      </a>
      <a href="javascript:;" class="guide_item" :class="{on: $route.path==='./cart'}" @click="goTo('/cart')">
        <span class="item_icon">
          <i class="iconfont icon-14shopcar"></i>
        </span>
        <span>购物车</span>
      </a>
      <a href="javascript:;" class="guide_item" :class="{on: $route.path==='./profile'}" @click="goTo('/profile')">
        <span class="item_icon">
          <i class="iconfont con-personal"></i>
        </span>
        <span>个人</span>
      </a>
    </footer>
</template>

<script>
  export default {

  }
</script>
<style lang="stylus" rel="stylesheet/stylus" scoped>


</style>
