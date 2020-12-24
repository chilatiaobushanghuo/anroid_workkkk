<template>
	<view>
		<view class="denglu">
			<view class="yonghuming">
				<button type="default">用户名：</button>
				<input type="text" value="请输入你的用户名" />
			</view>
			<view class="mima">
				<button type="default">密码：</button>
				<input type="text" value="请输入你的密码"/>
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
.denglu{
	display: flex;
	flex-direction: column;
}
.yonghuming{
	display: flex;
}
.mima{
	display: flex;
}
</style>
