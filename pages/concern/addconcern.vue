<template>
	<view class="containner">
		<view class="top">
			
		<navigator open-type="navigateBack">
		<image src="../../static/jiantou.png" class="left" ></image>
		</navigator>
		<span class="top-title">推荐关注</span>
		</view>
		<view class="secondtop">
			<view class="top-second">
                <image src="../../static/a1.png" class="pic"></image> 	</br>	
						<span class="wenzi">推荐作者</span>
			</view>
			
		</view>
	</view>
</template>

<script>
	export default {
		data() {
			return {
				
			}
			}
			}
</script>

<style>
	.left{ 
	
			width: 30px;
			height: 30px;
	}
		
	.top-title{
		margin-left: 15px;
		text-align: center;
	}
		
	.top{
		
		margin-left: 20px;
		padding-top: 40px;
		display: flex;
	}
	.pic{
		width: 30px;
		height: 30px;
		text-align: center;
	}
	.wenzi{
		 font-size: 15px;
	}
	.secondtop{
		padding-top: 20px;
	}
</style>
