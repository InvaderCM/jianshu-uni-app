<template>
	<view class="containner">
		<view class="top">
			<view class="left">
				<view class="top-box">
					<image src="../../static/left.png" class="sign"></image>
					<span class="title">我的文章</span>
				</view>

			</view>
			<view class="right">
				<image src="../../static/search.png" class="sign1"></image>
			</view>
		</view>
		<view class="content">
			<view class="box">
				<view class="box-left">
					<p class="box-title">公开文章</p>
				</view>
				<view class="box-right">
					<p class="box-title1">私密文章</p>
				</view>
			</view>
			<view class="box1">
				<span class="total">12篇文章</span>
				<span class="see">查看公开文章</span>
			</view>
			<view class="item">
				<p class="item-time">03.21 10:07</p>
				<h4 class="item-title">SPA：单页应用</h4>
			</view>
			<view class="item">
				<p class="item-time">03.18 20：33</p>
				<h4 class="item-title">2019-03-18随堂笔记</h4>
			</view>
			<view class="item">
				<p class="item-time">03.18 08:07</p>
				<h4 class="item-title">9、前后端分离开发</h4>
			</view>
			<view class="item">
				<p class="item-time">03.06 17:22</p>
				<h4 class="item-title">7、在Spring 5中使用Unit单元测试</h4>
			</view>
			<view class="item">
				<p class="item-time">03.06 15:59</p>
				<h4 class="item-title">6、Spring IoC练习</h4>
			</view>
			<view class="item">
				<p class="item-time">03.06 13:52</p>
				<h4 class="item-title">Vue.js入门</h4>
			</view>
		</view>
	</view>
</template>

<script>

</script>

<style>
	.top {
		display: flex;
		justify-content: space-between;
		margin-top: 50upx;
		height: 75upx;
		border-bottom: 1upx solid #EEEEEE;
	}

	.sign {
		width: 40upx;
		height: 40upx;
		margin-left: 30upx;
		margin-top: 10upx;
	}

	.sign1 {
		width: 40upx;
		height: 40upx;
		margin-right: 30upx;
		margin-top: 10upx;
	}

	.title {
		font-size: 35upx;
		margin-left: 30upx;
	}

	.box {
		display: flex;
		justify-content: space-between;
		height: 90upx;
		border-bottom: 1upx solid #EEEEEE;
	}

	.box-title {
		font-size: 35upx;
		margin-left: 120upx;
		margin-top: 20upx;
	}

	.box-title1 {
		font-size: 35upx;
		margin-right: 120upx;
		margin-top: 20upx;
	}

	.box1 {
		height: 80upx;
		display: flex;
		justify-content: space-between;
		background-color: #EEEEEE;
	}

	.total {
		font-size: 25upx;
		color: #B4B4B4;
		margin-left: 50upx;
		margin-top: 20upx;
	}

	.see {
		font-size: 25upx;
		color: #B4B4B4;
		margin-right: 50upx;
		margin-top: 20upx;
	}

	.item {
		height: 160upx;
		border-bottom: 1upx solid #EEEEEE;
	}

	.item-time {
		color: #B4B4B4;
		font-size: 23upx;
		margin-left: 50upx;
		margin-top: 20upx;
	}

	.item-title {
		font-size: 40upx;
		margin-left: 50upx;
		margin-top: 5upx;
	}
</style>
