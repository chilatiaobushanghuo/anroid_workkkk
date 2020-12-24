<template>
	<view>
		<view class="kaishi">
				<image src="../../static/luxun.jpg" mode="" class="tupian"></image>
			<view class="mingyan">不满是向上的车轮——鲁迅
			</view>
		</view>
		<view class="biaoti">
			<text class="ziti">语言只是工具，重要的是思想</text>
		</view>
		<view class="gonglue">
			<view class="aa">点击图片获取正版书籍</view>
			<view class="cyuyan">
				<image src="../../static/suanfadaolun.jpg"  class="gonglue_tp" mode="widthFix"@click="g1"></image>
				<view class="wenzi_neirong">
				<text>书名：《算法导论》</text>
				<text>作者：科曼（Cormen,T.H.）等</text>
				<text>简评：全面、严谨的介绍计算机算法</text>	
				</view>				
			</view>
			<view class="cyuyan">
				<image src="../../static/shenruljie.jpg"  class="gonglue_tp" mode="widthFix"@click="g2"></image>
			<view class="wenzi_neirong">
			<text>书名：《深入理解计算机系统》</text>
			<text>作者：科曼（Cormen,T.H.）等</text>
			<text>简评：深入介绍计算机原理的不朽之作</text>	
			</view>	
			</view>
			<view class="cyuyan">
				<image src="../../static/daimadquan.jpg"  class="gonglue_tp" mode="widthFix"@click="g3"></image>
				<view class="wenzi_neirong">
				<text>书名：《代码大全》</text>
				<text>作者：史蒂夫·迈克康奈尔</text>
				<text>简评：项目规划者的开发指南</text>	
				</view>	
			</view>
			<view class="cyuyan">
				<image src="../../static/zhengjie.jpg"  class="gonglue_tp" mode="widthFix"@click="g4"></image>
				<view class="wenzi_neirong">
				<text>书名：《代码整洁之道》</text>
				<text>作者：Robert C.Martin</text>
				<text>简评：细节之中自有天地，整洁成就卓越代码</text>	
				</view>	
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
			g1()
			{
				uni.navigateTo({
				 url:"../goushu/g1/g1"
				})
			},
			g2()
			{
				uni.navigateTo({
				 url:"../goushu/g2/g2"
				})
			},
			g3()
			{
				uni.navigateTo({
				 url:"../goushu/g3/g3"
				})
			},
			g4()
			{
				uni.navigateTo({
				 url:"../goushu/g4/g4"
				})
			}
		}
	}
</script>
<style>
	 button::after{
	        border: none;
	    }
.kaishi{
	display: flex;
	margin: 30rpx;
	padding: 10rpx;
	background-color: #E6A23C;
	width: 80%;
	height: 240rpx;
	position:relative;
	left: 35rpx;
	
}
.tupian{
	margin-right: 20rpx;
	height: 220rpx;
	width: 250rpx;
	padding: 10rpx;
}
.mingyan{
	margin-left: 10rpx;
	font-size: large;
	align-items: center;
	display:table-cell;
	vertical-align:middle;
	position: relative;
	top:40rpx;
}
.gonglue{
	display: flex;
	flex-direction: column;
	background-color:#E1F3D8;
}
.cyuyan{
	display: flex;
	margin-bottom: 10rpx;
	padding: 10rpx;
	color: #000000;
}
.gonglue_c{
  
}
.gonglue_tp{
	height: 300rpx;
	width: 300rpx;
	margin-right: 30rpx;
	mode:"";
}
.biaoti{
	
	width: 100%;
	background-color: #FDE2E2;
	font-family:"楷体";
	font-size: large;
	text-align:center;
	align-items: center;
}
	.ziti{
		text-align: center;
	}
	.wenzi_neirong{
		display: flex;
		flex-direction: column;
	}
	.aa{
		position: relative;
		left: 200rpx;
	}
</style>
