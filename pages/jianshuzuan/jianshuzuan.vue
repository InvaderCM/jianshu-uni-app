<template>
	<view class="container">
		<view class="header">
			<image src="../../static/attention-active.png" mode=""></image>
			{{title}}
		</view>
		<view class="content">
			
		</view>
	</view>
</template>

<script>
	export default {
		data() {
			return {
				title:'wxy'
			}
		},
		onLoad() {
	
		},
		methods: {
	
		}
	}
</script>

<style scoped>
	.container{
		display: flex;
		flex-direction: column;
		height: 0 auto;
	}
	.header{
		display: flex;
		height: 30px;
		background: black;
	}
</style>
