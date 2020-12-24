<template>
	<view>
		<view class="jiesao_zheng">
			<image src="../../static/bg.jpg" mode="" class="jiesao_tp"></image>
			<view class="jiesao_wenzi">资源汇总</view>
		</view>
		<view class="biancheng">
		<view class="xuexi">
			<image src="../../static/1.jpg" mode=""></image>
			Udacity 是一个自学编程网站，它的中文名字叫优达学城，你可以在上面学习HTML，CSS，Javascript，Python， Java 和其他编程语言，它上面的课程大都是硅谷著名公司（像Google，Facebook 等等）的技术专家来教学的，而且很多课程都有翻译字幕。
			<button type="default"@click="d1">点击进入该网站</button>
		</view>
		<view class="xuexi">
			<image src="../../static/2.jpg" mode=""></image>
			edX是一个由麻省理工学院和哈佛大学在2012 年联合创办的大规模开放在线课堂平台。它免费给大众提供大学教育水平的在线课堂，而且还是以非营利组织来运营的。虽然学习是免费的，但是一个课程学习完成，认证却是需要收费的，经过四年的发展，edX已经有48 所大学参与其中，包括国内的清华大学和北京大学。
			<button type="default"@click="d2">点击进入该网站</button>
		</view>
		<view class="xuexi">
			<image src="../../static/3.jpg" mode=""></image>
			Coursera 是由斯坦福大学两位计算机教授创办的在线教育平台，其中一位是一位美籍华人，Coursera 上现有28个不同国家和地区的145所不同的大学，课程算是比较多的，而且好多课程提供中英文字幕，在国内的多个平台可以观看Coursera 的课程。而且Coursera 还提供科学的方法来教学，提供随机生成的测试，让学生反复学习和测试，直到其掌握所学知识。
			<button type="default"@click="d3">点击进入该网站</button>
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
			d2()
			{
				uni.navigateTo({
		         url:"../d2/d2"
				})
			},
			d1()
			{
				uni.navigateTo({
			     url:"../d1/d1"
				})
			},
			d3()
			{
				uni.navigateTo({
			     url:"../d3/d3"
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
.xuexi
{	
	display: flex;
	flex-direction: column;
}
.biancheng{
	padding: 60rpx;
	position: relative;
	right: 20rpx;
	bottom: 20rpx;
}
</style>
