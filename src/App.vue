<template>
  <div id="app" class="app-container">
    <!-- 顶部Header区域 -->
    <mt-header fixed title="固定在顶部"></mt-header>
    <!-- 中间路由区域 -->
    <router-view/>
    <!-- 底部tabbar区域路由区域 -->
    <nav class="mui-bar mui-bar-tab">
      <router-link to="/" class="mui-tab-item" exact-active-class="mui-active">
        <span class="mui-icon mui-icon-home"></span>
        <span class="mui-tab-label">首页</span>
      </router-link>

      <router-link to="/warframe" class="mui-tab-item" active-class="mui-active" >
        <span class="mui-icon mui-icon-email"></span>
        <span class="mui-tab-label">战甲</span>
      </router-link>

      <router-link class="mui-tab-item" to="/alert" active-class="mui-active">
        <span class="mui-icon mui-icon-contact"></span>
        <span class="mui-tab-label">警报</span>
      </router-link>

      <router-link class="mui-tab-item" to="/setting" active-class="mui-active">
        <span class="mui-icon mui-icon-gear"></span>
        <span class="mui-tab-label">设置</span>
      </router-link>
    </nav>
  </div>
</template>

<style lang="scss">
.app-container {
  padding-top: 40px;
}
</style>
