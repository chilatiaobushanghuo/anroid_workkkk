<template>
	<view>
		<view class="jiesao_zheng">
			<image src="../../static/bg.jpg" mode="" class="jiesao_tp"></image>
			<view class="jiesao_wenzi">学校推荐</view>
		</view>
		<view class="gonglue">
			<view class="cyuyan">
				<image src="../../static/sdnu.jpg" mode="" class="gonglue_tp"></image>
				<view class="wenzi_neirong">
					<text>学校:山东师范大学</text>
					<text>简称:SDNU</text>
					<text>特点:历史悠久，山东名校</text>
					<text>位置:济南</text>
					<text@click="c1">主页:sdnu.edu.cn/</text>
				</view>
			</view>
			<view class="cyuyan">
				<image src="../../static/qinghua.jpg" mode="" class="gonglue_tp"></image>
				<view class="wenzi_neirong">
					<text>学校:清华大学</text>
					<text>简称:THU</text>
					<text>特点:中国第一名校</text>
					<text>位置:北京</text>
					<text@click="c2">主页:tsinghua.edu.cn/</text>
				</view>
			</view>
			<view class="cyuyan">
				<image src="../../static/huazhongkeji.jpg" mode="" class="gonglue_tp"></image>
				<view class="wenzi_neirong">
					<text>学校:华中科技大学</text>
					<text>简称:HUST</text>
					<text>特点:计算机全国前列</text>
					<text>位置:武汉</text>
					<text@click="c3">主页:hust.edu.cn/</text>
				</view>
			</view>
			<view class="cyuyan">
				<image src="../../static/nanjing.jpg" mode="" class="gonglue_tp"></image>
				<view class="wenzi_neirong">
					<text>学校:南京邮电大学</text>
					<text>简称:NJUPT</text>
					<text>特点:著名的“南邮”</text>
					<text>位置:南京</text>
					<text@click="c4">主页:njupt.edu.cn/</text>
				</view>
			</view>
			<view class="cyuyan">
				<image src="../../static/beili.jpg" mode="" class="gonglue_tp"></image>
				<view class="wenzi_neirong">
					<text>学校:北京理工大学</text>
					<text>简称:BIT</text>
					<text>特点:著名985高校</text>
					<text>位置:北京</text>
					<text@click="c5">主页:bupt.edu.cn/</text>
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
			c1()
			{
				uni.navigateTo({
				 url:"../xuexiaozhuye/x1/x1"
				})
		},
		c2()
			{
				uni.navigateTo({
				 url:"../xuexiaozhuye/x2/x2"
				})
		},c3()
			{
				uni.navigateTo({
				 url:"../xuexiaozhuye/x3/x3"
				})
		},
		c4()
			{
				uni.navigateTo({
				 url:"../xuexiaozhuye/x4/x4"
				})
		},
		c5()
			{
				uni.navigateTo({
				 url:"../xuexiaozhuye/x5/x5"
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
.tuijian{
	display: flex;
}
.SDNU{
	display: flex;
	flex-direction: column;
	margin: 30rpx;
}
.tupian{
	
}
.wenzi{
	
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
	background-color: #007AFF;
	position: relative;
	bottom: 100rpx;
}
.cyuyan{
	display: flex;
	margin-bottom: 10rpx;
	padding: 10rpx;
	color: #E1F3D8;
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
		font-size: 15px;
	}
</style>
