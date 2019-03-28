<template>
	<view class="containner">
       <view class="top">
       	<text class="top-title">关注</text>
       	<image class="add-friend" src="../../static/add.png"></image>
       	<image class="search" src="../../static/search.png"></image>
       </view>
	   <image src="../../static/c10.jpg" class="c10"></image>
	   <view class="bigcard">
	   	<view class="card" v-for="(book, index) in books" :key="index">
	   		<img class="touxiang" :src="book.cover" />
	   		<span class="name">{{ book.name }}</span>
	   		<br />
	   		<span class="word">{{ book.word }}</span>
	   		<br />
			
	   	</view>
		     <image src="../../static/c9.jpg" class="c9"></image>
			 <view class="end">
				
				 <navigator url="addconcern" hover-class="navigator-hover">
	 <span class="e">去发现</span><span class="e e1">更多有趣的作者和专题 >></span>
				 </navigator>
			 </view>
	   </view>
	</view>
</template>

<script>
	export default {
		data() {
			return {
				books:[
					{
						 name:'读书',
						 word:'《朗读者3》董娜-电子书在线阅读',
						 cover:'static/cover1.jpg'
						
					},
					{
						 name:'旅行·在路上',
						 word:'走进非洲踏上诶及，开罗第一天的观感让人不..',
						 cover:'static/cover2.png'
						
					},
					{
						 name:'摄影',
						 word:'小楼',
						 cover:'static/cover3.jpg'
						
					},
					{
						 name:'简书电影',
						 word:'《都挺好》揭开一个现实的真相，越是优秀...',
						 cover:'static/cover4.jpg'
						
					},
					{
						 name:'@IT·互联网',
						 word:'火币昨天赚钱的是这几波人---',
						 cover:'static/cover5.jpg'
						
					},
					{
						 name:'故事',
						 word:'菩萨',
						 cover:'static/cover6.jpg'
						
					},
					{
						 name:'错过_',
						 word:'2019-03-27',
						 cover:'static/cover7.jpg'
						
					},
					{
						 name:'陶然然_niit',
						 word:'7 Spring Boot项目打包运行',
						 cover:'static/cover8.jpg'
						
					},
					
				]
			};
		},
		onLoad() {

		},
		onLoad() {},
		methods: {}
	};
</script>

<style>
	.containner {

		height: 400upx;
	}
    .logo{
        height: 200upx;
        width: 200upx;
        margin-top: 200upx;
    }
	.top-title{
		margin-left: 10px;
		font-size: 18px;
		color: black;
	}
	.add-friend{
		width: 50upx;
		height: 50upx;
		margin-left:500upx;
	}
	.search{
		width: 50upx;
		height: 50upx;
		margin-left: 25upx;
	
	}
	.top{
		padding-top: 40px;
		display: flex;
		align-items: center;
		
	}
	
	.touxiang {
		width: 50px;
		height: 50px;
		float: left;
		margin-left: 20px;
		border-radius: 10px;
		marker-end: 5px;
	}
	.name{
		margin-left: 20px;
		
	}
	.word{
		margin-left: 20px;
		font-size: 12px;
		color:#B4B4B4 ;
	}
	.bigcard {
		width: 100%;
		height: 450px;
		margin: 0 auto;
		background-color: white;
		border-color: #A9A9A9;
	}
	
	.card {
		text-align: left;
		margin-left: 10px;
		margin-right: 10px;
		font-size: 14px;
		line-height: 20px;
	   	border: #B4B4B4  1upx solid;
	   border-left: 0px;
	   border-right: 0px;
	   border-top: 0px;
	   height: 60px;
	   padding-top: 10px;
		
	}
		
	.c9{
		width: 250px;
		height: 150px;
		margin-left: 50px;
	}
	.c10{
		height: 40px;
		width: 360px;
		margin-top: 5px;
	}
	.e{
		font-size: 14px;
	}
	.e1{
		color: #7667C7;
	}
	.end{
		text-align: center;
	}
</style>

