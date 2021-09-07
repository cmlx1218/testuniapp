<template>
	<view>
		<view>
			鬼马
		</view>
		<!-- text使用 -->
		<view>
			<text>牛转乾坤</text>
		</view>
		<view>
			<!-- 文本是否可选 -->
			<text selectable>牛转乾坤1</text>
		</view>
		<view>
			<!-- 中文字符一半大小 -->
			<text space="ensp">牛转  乾坤2</text>
		</view>
		<view>
			<!-- 中文字符相同大小 -->
			<text space="emsp">牛转  乾坤3</text>
		</view>
		<view>
			<!-- 空格大小 -->
			<text space="nbsp">牛转  乾坤3</text>
		</view>
		
		
		<!-- view 使用    hover-class按下去添加的样式类  -->
		<view class="bigbox" hover-class="bigbox-s">
			<!--   hover-stop-propagation 阻止冒泡  -->
			<view class="box" hover-class="box-s" hover-stop-propagation>盒子</view>
		</view>
		<!-- hover-start-time按下多少秒后执行   hover-stay-time松开多少秒后执行  -->
		<view class="time" hover-class="time-a" hover-start-time="2000" hover-stay-time="2000">时间管理</view>
		
		
		<!-- 按钮 -->
		<button>按钮</button>
		<button size="mini">按钮大小</button>
		<button size="mini" type="primary">按钮颜色</button>
		<button size="mini" type="primary" plain>按钮镂空</button>
		<button size="mini" type="primary" plain disabled>按钮禁用</button>
		<button loading></button>
		
		<!-- image  默认宽300px 高225px -->
		<image src="http://destiny001.gitee.io/image/cxk.gif"></image>
		<!--  mode="aspectFit"  完整显示图片  -->
		<image mode="aspectFit" src="http://destiny001.gitee.io/image/cxk.gif"></image>
		<!-- 长边完全显示   -->
		<image mode="aspectFill" src="http://destiny001.gitee.io/image/cxk.gif"></image>
		
	</view>
</template>

<script>
</script>

<style>
	.box{
		width: 100px;
		height: 100px;
		background-color: #808080;
	}
	.box-s{
		background-color: red;
	}
	.bigbox{
		width: 200px;
		height: 200px;
		background-color: #007AFF;
	}
	.bigbox-s{
		background-color: #4CD964;
	}
	.time{
		width: 200px;
		height: 200px;
		background-color: #DD524D;
	}
	.time-a{
		background-color: #555555;
	}
</style>
