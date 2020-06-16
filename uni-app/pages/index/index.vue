<template>
	<view class="content">
		<!-- 图标演示
		<text class="iconfont icon-shouye" style="font-size: 100rpx"></text> -->
		<!-- 动画使用 点击效果 -->
		<view style="display: flex;justify-content: center;padding: 50rpx;">
			<view class="animated faster" hover-class="rubberBand" 
			style="border: 1rpx solid #CCCCCC;padding: 20rpx;">
				点击效果
			</view>
		</view>
		
	</view>
</template>

<script>
	// 这是注释
	export default {
		data() {
			return {
				title: 'Hello'
			}
		},
		onLoad() {

		},
		methods: {

		}
	}
</script>

<style>
	
</style>
