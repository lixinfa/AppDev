<template>
  <div id="app">
		<!-- 第三步使用组件 -->
		<tabbar>
			
		</tabbar>
		
  </div>
</template>

<script>
//第一步导入组件
	import tabbar from './components/tabbar/tabbar.vue'



export default {
  name: 'app',
  components: {
		// 第二步注册组件
		
				tabbar
  }
}
</script>

<style>
	@import url("./assets/css/base.css");
	
</style>
