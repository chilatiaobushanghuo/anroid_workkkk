<template>
	<view>
		<view class="kaishi_zheng">
			<view class="kaishi">
				<image class='huanyingtupian' src="../../static/timg.jpg" mode="widthFix"></image>
			</view>
			<view class="kafei">
				制作不易，请我喝杯咖啡吧
			</view>
		</view>
		<view class="jianjie">
		<text>简介：该项目是自主开发，专为计算机学子打造的一款ap</text>
		<text>p,由于制作者前端知识比较匮乏，前端开发经验不足，所</text>
		<text>所以，界面比较“丑”，功能也相对简单，之后会继续完善.</text>	
		<text>望见谅！</text>
		</view>
		<view class="dashang">
			<view class="weixin_zheng">
				<image src="../../static/weixin.png" mode="" class="wxtp"></image>
				<text class="weixin_wenzi"></text>
			</view>
			<view class="zhifubao_zheng">
				<image src="../../static/zhifubao.jpg" mode="" class="zhifubaotp"></image>
				<text class="weixin_wenzi"></text>
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
			
		}
	}
</script>

<style>
.pingjia{
	text-aglin:center;
}
.kafei{
	position: relative;
	bottom: 370rpx;
	font-size: large;
	text-align: center;
}
.kaishi_zheng{
	
}
.jianjie{
	margin-left: 20rpx;
	margin-right: 20rpx;
	margin-bottom: 20rpx;
	background-color: #FFA200;
	position: relative;
	bottom: 60rpx;
	padding: 20rpx;
}
.dashang{
	padding: 10rpx;
	display: flex;
	position: relative;
	left: 30rpx;
}
.weixin_zheng{
padding: 10rpx;
	margin-right: 10rpx;
	margin-left: 10rpx;
}
.wxtp{
	width:300rpx;
	height: 300rpx;
}
.weixin_wenzi{
	width:40rpx;
	height: 40rpx;
}
.zhifubao_zheng{
	padding: 10rpx;
	margin-left: 10rpx;
	position: relative;
	bottom: 53rpx;
}
.zhishi_wenzi{
	
}
.zhifubaotp{
	width:300rpx;
	height: 300rpx;
}
</style>
