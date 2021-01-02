<template>
	<view class="content">
		<image class="head_portrait" src="../../static/img/头像.jpg"></image>
		
		<table>
			<th>最近文章</th>
			<tr></tr>
		</table>
		
		<table>
			<tr>简历</tr>
			<tr>个人主页</tr>
		</table>
	</view>
</template>

<script>
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
	.content {
		display: flex;
		flex-direction: column;
		align-items: center;
		justify-content: center;
	}

	.head_portrait {
		height: 300rpx;
		width: 300rpx;
		margin-top: 100rpx;
		margin-left: auto;
		margin-right: auto;
		margin-bottom: 50rpx;
		 border-radius: 100%;
	}

	.text-area {
		display: flex;
		justify-content: center;
	}

	.title {
		font-size: 36rpx;
		color: #8f8f94;
	}
</style>
