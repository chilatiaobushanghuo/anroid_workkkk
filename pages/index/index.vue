<template>
    <view class="bg">
		<view class="kaishi">
			<image class='huanyingtupian' src="../../static/logo.jpg" mode="widthFix"></image>
			<view class="huanying">您好，欢迎来到我的APP</view>
		</view>
		<view class="mingyan">
			<text class='shuai'>业精于勤,荒于嬉;行成于思,毁于随。</text>
		</view>
		<view class="zhuyao">
			<view class="left">
				<view class="xuexiao_zheng">
					<image src="../../static/school.png" mode="" class="xuexiao"></image>
					<text class="xuexiao_wenzi"@tap="xuexiao">学校推荐</text>
				</view>
				<view class="tuijian_zheng">
					<image src="../../static/tuijian.png" mode="" class="tuijian"></image>
					<text class="tuijian_wenzi"@tap="ziyuan">资源</text>
				</view>
			</view>
			<view class="right">
				<image src="../../static/book.png" mode="" class="zishi"></image>
				<text class="zhishi_wenzi"@tap="zhishi">基础知识</text>
			</view>
		</view>
    </view>
</template>
<script>
	export default {
		data() {
			return {
			}
		},
		methods: {
			xuexiao()
			{
				uni.navigateTo({url:'../xuexiao/xuexiao'})
			},
			ziyuan()
			{
				uni.navigateTo({
					url:'../ziyuan/ziyuan'
				})
			},
			zhishi()
			{
				uni.navigateTo({
					url:'../zhishi/zhishi'
				})
			}
		}
	}
</script>
<style>
	.huanying{
		position: absolute;
		top: 60rpx;
		left: 40rpx;
		color: #FFFFFF;
		
	}
	.huanyingtupian{
		width: 100%;
	}
	.juesejies{
		display: flex;
		align-items: center;
		padding-left: 40%;
		font-size: large;
	}
	.mingyan{
		 text-align:center;
		  background-color:#F0AD4E;
	}
	.shuai{
		font-family:cursive;text-shadow:6px 2px 2px #333;color:deeppink;
		font-size:large;
		text-aglin:center;
	}
	.lianxi{
		display: flex;
	}
	.qq-img{
		width: 50rpx;
		height: 50rpx;
	}
	.qq-text{
		padding: 10rpx,10rpx,10rpx,10rpx;
	}
	.left{
		width: 290rpx;
		margin-right: 20rpx;
		display: flex;
		padding: 0 20rpx;
		flex-direction: column;
		font-size:medium;
		color:#007AFF;
		justify-content: center;
		padding:  0,0,10rpx,100rpx;
		margin-right: 30rpx;
	}
	.right{
		width: 340rpx;
		display: flex;
		flex-direction: column;
		justify-content: center;
	}
	.xuexiao{
	width: 200rpx;
	height: 200rpx;
    margin-right: 10rpx;
	position: relative;
	left:70rpx;
	margin-bottom: 60rpx;
	}
	.tuijian{
		width: 200rpx;
		height: 200rpx;
		margin-right: 10rpx;
		position: relative;
		left:70rpx;
		margin-bottom: 60rpx;
	}
	.zishi{
		width: 400rpx;
		height: 400rpx;
		padding:  0,0,10rpx,100rpx;
		position: relative;
		right: 20rpx;
	}
	.zhuyao{
		display: flex;
		flex-direction: row;
		background-color: #F2F2E6;
		height: 620rpx;
	}
	.xuexiao_wenzi{
	font-size: medium;
	position: relative;
	left: 80rpx;
	bottom: 70rpx;
	}	
	.zhishi_wenzi{
		font-size: large;
		position: relative;
		color:#007AFF;
		left: 80rpx;
	}
	.tuijian_wenzi{
		font-size: medium;
		position: relative;
		right: 90rpx;
		bottom: 20rpx;
		
	}
	.xuexiao_zheng{
		margin-bottom: 10rpx;
		display: flex;
		flex-direction: column;
		position: relative;
		top:80rpx;
	}
	.tuijian_zheng{
		position: relative;
		flex-direction: column;
	}
	.bg{
		background-color:#F0AD4E;
	}
</style>
