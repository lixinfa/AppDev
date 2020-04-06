<template>
	<div id="tabbar">
						 <div class="tabbar-item">首页</div>
						 <div class="tabbar-item">购物车</div>
						 <div class="tabbar-item">首页</div>
						 <div class="tabbar-item">我的</div>
				 </div>   
</template>

<script>
</script>

<style scoped="scoped">
	#tabbar{
			display: flex;
			background-color: #ffaa7f;
			left: 0;
			right: 0;
			height: 3.0625rem;
			bottom: 0;
			box-shadow: 0px,-3px,3px,rgba(100,100,100,.8);
			position: fixed;
			}
		.tabbar-item{
			flex: 1;
			text-align: center;
		
		}

</style>
