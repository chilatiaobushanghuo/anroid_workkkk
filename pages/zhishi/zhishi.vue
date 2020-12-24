<template>
	<view>
		<view class="jiesao_zheng">
			<image src="../../static/bg.jpg" mode="" class="jiesao_tp"></image>
			<view class="jiesao_wenzi">基础知识</view>
		</view>
		<view class="" class="zuti">
			<text class="biaoti">考研招生信息</text>
			<view class="" @click="z1">
				山东师范大学：http://www.yjszs.sdnu.edu.cn/info/1009/1771.htm
			</view>
			<view class="" @click="z2">
				清华大学：http://yz.tsinghua.edu.cn/info/1013/1169.htm
			</view>
			<view class="" @click="z3">
				山东大学：https://www.yz.sdu.edu.cn/info/1034/4317.htm
			</view>
		</view>
		<view class="" class="zuti">
			<text class="biaoti">考研建议</text>
			<view class="" @click="z4">
				知乎高赞：22届考研，现在可以先开始准备哪些方面的东西？
			</view>
			<view class="" @click="z5">
				微博置顶：22考研的同学现阶段如何记单词？
			</view>
			<view class="" @click="z6">
				B站推荐课：李永乐老师的考研复习规划
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
			z1()
			{
				uni.navigateTo({
					url:"../z1/z1"
				})
			},
			z2()
			{
				uni.navigateTo({
					url:"../z2/z2"
				})
			},
			z3()
			{
				uni.navigateTo({
					url:"../z3/z3"
				})
			},
			z4()
			{
				uni.navigateTo({
					url:"../z4/z4"
				})
			},
			z5()
			{
				uni.navigateTo({
					url:"../z5/z5"
				})
			},
			z6()
			{
				uni.navigateTo({
					url:"../z6/z6"
				})
			}
		}
	}
</script>

<style>
.jiesao_tp{
	width: 100%;
	height: 200rpx;
}
.jiesao_wenzi{

	    background-image: -webkit-linear-gradient(left,blue,#66ffff 10%,#cc00ff 20%,#CC00CC 30%, #CCCCFF 40%, #00FFFF 50%,#CCCCFF 60%,#CC00CC 70%,#CC00FF 80%,#66FFFF 90%,blue 100%);
	    -webkit-text-fill-color: transparent;/* 将字体设置成透明色 */
	    -webkit-background-clip: text;/* 裁剪背景图，使文字作为裁剪区域向外裁剪 */
	    -webkit-background-size: 200% 100%; 
	    -webkit-animation: masked-animation 4s linear infinite;
	    font-size: 35px;
		position: relative;
		bottom: 180rpx;
		left: 200rpx;
}
.zuti{
	background-color: #67C23A;
	position: relative;
	bottom: 150rpx;
	margin: 40rpx;
	padding: 20rpx;
}
.biaoti{
	font-size: large;
	text-align: center;
	position: relative;
	left: 200rpx;
}
</style>
