<template>
	<view>
		<view class="text">
			龙王
		</view>
		
		<view class="box"></view>
	</view>
</template>

<script>
	export default{
		data() {
			return {
				msg: 'hello'
			}
		},
		
		onLoad() {
			uni.onNetworkStatusChange(function (res) {
			    console.log(res.isConnected);
			    console.log(res.networkType);
				console.log(1)
			});
	
			console.log('页面加载了')
		},
		onShow(){
			uni.onNetworkStatusChange(function (res) {
			    console.log(res.isConnected);
			    console.log(res.networkType);
				console.log(1)
			});
		},
		methods:{
			
		}
	}
</script>

<style>
	@import url("./longwang.css");//导入css
	.box{
		width: 375rpx;
		height: 375rpx;
		background-color: #DD524D;
	}
</style>
