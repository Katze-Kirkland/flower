<template>
    <div id="footer" class="ft">
      <div class="ft-container">
        <!-- 尾部导航 -->
        <div class="ft-nav">
          <a href="/">首页</a>
          <a href="https://www.xianhuawang.net/" target="_blank">关于我们</a>
          <a href="https://www.xianhuawang.net/" target="_blank">媒体报道</a>
          <a href="https://www.xianhuawang.net/" target="_blank">企业团购</a>
          <a href="https://www.xianhuawang.net/" target="_blank">花店入驻</a>
          <a href="https://www.xianhuawang.net/" target="_blank">友情链接</a>
          <a href="https://www.xianhuawang.net/" target="_blank">在线补款</a>
          <a href="https://www.xianhuawang.net/" target="_blank">为什么选择鲜花网</a>
        </div>
        <!-- 尾部导航 End -->
      </div>
    </div>
  </template>
  
  <script lang="ts" setup> 
  </script>
  
  <style lang="scss">
  #footer {
    font-size: 0;
    background-color: #232628;
    .ft-container {
      width: 1200px;
      margin: 0 auto;
      padding: 40px 0 46px;
      .ft-nav {
        a {
          display: inline-block;
          font-size: 16px;
          line-height: 16px;
          color: #fff;
        }
        a + a {
          padding-left: 28px;
          margin-left: 33px;
          border-left: 1px solid #fff;
        }
      }
        a {
          font-size: 12px;
          line-height: 16px;
          color: #71797f;
          margin: 0 2px;
        }
      }
    }
  </style>