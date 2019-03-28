<template>
	<view class="containner">
		<view class="top">
			<view class="left">
				<image src="../../static/left.png" class="sign"></image>
				<span class="title">喜欢收藏</span>
			</view>
		</view>
		<view class="content">
			<view class="box">
				<view class="box-left">
					<p class="box-title">喜欢文章</p>
				</view>
				<view class="box-right">
					<p class="box-title1">收藏文章</p>
				</view>
			</view>

			<view class="item">
				<p class="item-name">
					七夏港_f3ef
					<span class="item-time">03.01 20:57</span>
				</p>
				<h4 class="item-title">4.以注解方式开发bean</h4>
			</view>
			<view class="item">
				<p class="item-name">
					六年的承诺
					<span class="item-time">03.01 20:57</span>
				</p>
				<h4 class="item-title">day01 Spring起步</h4>
			</view>
			<view class="item">
				<p class="item-name">
					七夏港_f3ef
					<span class="item-time">03.01 20:21</span>
				</p>
				<h4 class="item-title">Git初步</h4>
			</view>
			<view class="item">
				<p class="item-name">
					六年的承诺
					<span class="item-time">03.01 20:57</span>
				</p>
				<h4 class="item-title">以注解方式开发bean</h4>
			</view>
			<view class="item">
				<p class="item-name">
					七夏港_f3ef
					<span class="item-time">03.01 20:21</span>
				</p>
				<h4 class="item-title">6、Spring IoC练习</h4>
			</view>
			<view class="item">
				<p class="item-name">
					七夏港_f3ef
					<span class="item-time">03.01 20:21</span>
				</p>
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

	.item {
		height: 160upx;
		border-bottom: 1upx solid #EEEEEE;
	}

	.item-time {
		color: #B4B4B4;
		font-size: 23upx;
		margin-left: 20upx;
		margin-top: 20upx;
	}

	.item-title {
		font-size: 40upx;
		margin-left: 50upx;
		margin-top: 5upx;
	}

	.item-name {
		color: lightblue;
		font-size: 23upx;
		margin-left: 50upx;
		margin-top: 20upx;
	}
</style>
