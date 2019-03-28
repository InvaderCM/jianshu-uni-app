<template>
	<view class="content">
		<view class="header">
			<view>
				<h2 class="text-1">消息</h2>
			</view>
			<view>
				<image src="../../static/settings.png"></image>
				<image src="../../static/searcher.png"></image>
			</view>
		</view>
		<view class="top">
			<view class="text-2">
				<image src="../../static/message-active.png"></image>
				<h2 class="tet">互动消息</h2>
			</view>
			<view class="text-3">
				<image src="../../static/logo1-active.png"></image>
				<h2 class="tet-1">简书钻</h2>
			</view>
			<view class="text-4">
				<image src="../../static/other.png"></image>
				<h2 class="tet-2">其他提醒</h2>
			</view>
		</view>
		<view class="card">
			<image src="../../static/question.png"></image>
			<h2>如何免费获取简书钻</h2>
			<h2 class="text-5">查看详情</h2>
		</view>
		<view class="card1">
			<h2>#1 每天写文章，给文章点喜欢;</h2>
			<h2>#2 找到优质好文章，给文章点喜欢;</h2>
			<h2>#3 分享自己的文章,让其他人点喜欢;</h2>
		</view>
		<hr class="line"/>
		<view class="card2">
			<view class="card3">
				<view>
					<p>简信</p>
				</view>
				<view>
					<p>新简信</p>
				</view>
			</view>
			<view class="card4">
				<image src="../../static/information.png"></image>
			</view>
		</view>
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
	.top{
		display:flex;
	}
	.top image{
		width: 80upx;
		height: 80upx;
		margin-left:110upx;
		}
		.text{
			display: flex;
			padding-right: 50upx;
			border-bottom: 1upx solid #B4B4B4;
		}
	.header {
		position: fixed;
		top: 0;
		width: 100%;
		height: 100px;
		display: flex;
		justify-content: space-between;
		background-color: #ededed;
		color: #444;
		position: relative;
		top: -60upx;
	}
	.tet,.tet-1,.tet-2{
		margin-left: 100upx;
		font-size: 30upx;
	}
	.header image {
		width: 50upx;
		height: 50upx;
		margin-right: 30upx;
		padding-top: 100upx;
	}
	.text-1{
		position: relative;
		top: 60px;
		margin-left: 30upx;
	}
	.card{
		display: flex;
		font-size: 35upx;
		margin-top:50upx ;
		font-weight: 200;
	}
	.card1{
		font-size: 25upx;
		margin-top:40upx ;
		border-bottom: 10upx solid #B4B4B4;
	}
	.card image{
		width: 35upx;
		height: 35upx;
	}
	.card2{
		display: flex;
		border-top: 1upx solid #B4B4B4;
	}
	.card3{
		display: flex;
	}
	.card4 image{
		text-align: center;
		margin-top: 30upx;
		
		}
</style>
