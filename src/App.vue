<template>
  <div id="app">
    <!-- Header头部区域 -->
    <header class="mui-bar mui-bar-nav">
			<!-- <a class="mui-action-back mui-icon mui-icon-left-nav mui-pull-left"></a> -->
			<h1 class="mui-title">第一个VUE项目</h1>
		</header>
    <!-- 中间路由区域 -->
    <h1>测试</h1>
    <!-- Footer尾部区域 -->
    <nav class="mui-bar mui-bar-tab">
			<a class="mui-tab-item mui-active" href="#tabbar">
				<span class="mui-icon mui-icon-home"></span>
				<span class="mui-tab-label">首页</span>
			</a>
			<a class="mui-tab-item" href="#tabbar-with-chat">
				<span class="mui-icon mui-icon-email"><span class="mui-badge">9</span></span>
				<span class="mui-tab-label">消息</span>
			</a>
			<a class="mui-tab-item" href="#tabbar-with-contact">
				<span class="mui-icon mui-icon-contact"></span>
				<span class="mui-tab-label">通讯录</span>
			</a>
			<a class="mui-tab-item" href="#tabbar-with-map">
				<span class="mui-icon mui-icon-gear"></span>
				<span class="mui-tab-label">设置</span>
			</a>
		</nav>
  </div>
</template>
<script>

export default {
};
</script>
<style lang="scss">
  #app{
    padding-top: 44px;
  }
</style>
