<template>
  <div class="header">
    <div class="header-left">
      <div class="iconfont back-icon">&#xe624;</div>
    </div>
    <div class="header-input">
      <span class="iconfont search-icon">&#xe632;</span>输入城市/景点/游玩主题
    </div>
    <div class="header-right">
      北京<span class="iconfont arrow-icon">&#xe615;</span>
    </div>
  </div>
</template>

<script>
export default {
  name:"HomeHeader"
}
</script>

<style lang="stylus" scoped>
  @import '~style/varible.styl'
  .header
    display: flex
    height:.88rem
    background: $bgColor
    line-height: .88rem
    color:#fff
    .header-left
      width:.8rem
      text-align:center
      margin-right:.2rem
      .back-icon
        font-size: .36rem
    .header-input
      width:100%
      height: .6rem
      line-height: .6rem
      background: #fff
      color:#ccc
      border-radius: .1rem
      margin-top: .14rem
      padding: 0 .1rem
      box-sizing:border-box
      .search-icon
        margin-right: .05rem
    .header-right
      width:1.28rem
      margin: 0 .2rem
      .arrow-icon
        font-size: .24rem
        margin-left: .08rem
</style>
