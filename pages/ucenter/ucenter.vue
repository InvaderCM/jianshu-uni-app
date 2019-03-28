<template>

	<view class="content">
		<view class="top-t"></view>
		<view class="top">
			<view class="title">
				<image src="../../static/scan.png"></image>
			</view>
			<view class="night">
				<image src="../../static/night.png"></image>
			</view>
		</view>
		<view class="infor">
			<image src="../../static/me.jpg"></image>
			<text class="username">{{username}}</text><br>
			<text class="foncus">{{foncus}}</text>
			<text class="fans">{{fans}}</text>

		</view>
		<view class="fir_top">
			<image src="../../static/fir_top.jpg"></image>
		</view>

		<view class="sec_top">
			<view class="sec1">
				<navigator url="my_article" hover-class="navigator-hover">
					<image src="../../static/sec1.png" />
					<br />
					<text class="top-text-sao">我的文章</text>
				</navigator>
			</view>

			<view class="sec1">
				<image src="../../static/sec2.png" />
				<br />
				<text class="top-text-sao">我的书架</text>
			</view>

			<view class="sec1">
				<navigator url="my_love" hover-class="navigator-hover">
					<image src="../../static/sec3.png" />
					<br />
					<text class="top-text-sao">喜欢收藏</text>
				</navigator>
			</view>

			<view class="sec1">
				<navigator url="task" hover-class="navigator-hover">
				<image src="../../static/sec4.png" />
				<br />
				<text class="top-text-sao">有奖任务</text>
				</navigator>
			</view>
		</view>

		<view class="th_top">
			<image src="../../static/th_top.jpg"></image>
		</view>
		<view class="fou_top">
			<image src="../../static/fou_top.jpg"></image>
		</view>
		<!-- <navigator url="mine" hover-class="navigator-hover"> -->
		<view class="item" v-for="(user,index) in users" :key="index">
			<view class="right">{{user.name}}</view>
			<view class=" fontcard">
				<span class="word">{{ user.word }}</span>
				<br />
			</view>
		</view>
	</view>
	<!-- </navigator> -->
</template>

<script>
	export default {
		data() {
			return {
				title: '',
				night: '         夜间',
				username: '1只念旧的兔子',
				foncus: '关注  11',
				fans: '粉丝  12',

				users: [{
						name: '简书会员',
						word: '随时赠简书钻',
					},
					{
						name: '简书活动',
						word: '万元奖金等你',
					},
					{
						name: '简东西',
						word: '简书人都爱买',
					},
					{
						name: '我的钱包',
					},
					{
						name: '我的专题/文集',
					},

					{
						name: '浏览历史',
					},
					{
						name: '设置',
					},
					{
						name: '帮助反馈',
						word: '有问题找这里',
					}
				]


			}
		},
		onLoad() {

		},
		methods: {

		}
	}
</script>

<style>
	.top-t {
		width: 100%;
		height: 60upx;
	}

	.top {
		display: flex;
		height: 50upx;
		justify-content: space-between;
	}

	.infor {
		border-top: 1upx solid #00000;
		display: flex;
		height: 180upx;
		padding-top: 40upx;
	}

	.infor image {
		margin-left: 30upx;
		width: 120upx;
		height: 120upx;
		border-radius: 5px;
	}

	.username {
		margin-top: 10upx;
		margin-left: 50upx;
	}

	.fir_top {
		width: 100%;
		height: 100upx;
	}

	.fir_top image {
		width: 100%;
		height: 100%;
	}

	.sec1 {
		width: 60px;
		height: 28px;
		line-height: 28px;
		margin: 5px 15px;
		font-size: 10px;
		display: inline-block;
		;
		text-align: center;
		text-decoration: none;
	}

	.sec1 image {
		width: 23px;
		height: 23px;
		display: flex;
		margin-left: 30%;
		margin-right: 30%;
	}

	.th_top {
		width: 100%;
		height: 100upx;
	}

	.th_top image {
		width: 100%;
		height: 100%;
	}

	.fou_top {
		width: 100%;
		height: 100upx;
	}

	.fou_top image {
		width: 100%;
		height: 100%;
	}

	.item {
		width: 93%;
		display: row;
		font-size: 13px;
		height: 50upx;
		border: 1upx solid #eee;
		border-left: 0px;
		border-top: 0px;
		border-right: 0px;
		background-color: #fff;
		margin-left: 5px;
		padding-bottom: 30upx;
	}

	.word {
		width: 250px;
		height: 52px;
		border-top: 10px;
		border-right: 0px;
		border-left: 1px;
		font-size: 10px;
		border: 1upx solid #00000;
		margin-left: 570upx;
		margin-top: 10px;
		color: #8F8F94;
	}

	.right {
		margin-left: 20upx;
		margin-top: 50upx;
	}

	.title {
		margin-left: 30upx;
		margin-top: 20upx;
	}

	.title image {
		width: 23px;
		height: 23px;
		margin-right: 10px;
		margin-top: -60px;
	}

	.night {
		margin-right: 30upx;
		margin-top: 20upx;
	}

	.night image {
		width: 23px;
		height: 23px;
		margin-right: 10px;
		margin-top: -60px;
	}

	.foncus {
		font-size: 30upx;
		color: #8F8F94;
		margin-top: 50px;
		margin-right: 20px;
		line-height: 50rpx;
		text-align: -100px;
	}

	.fans {
		font-size: 30upx;
		color: #8F8F94;
		margin-top: 50px;
		line-height: 50rpx;
		text-align: -100px;
	}
</style>
