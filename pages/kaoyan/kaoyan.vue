<template>
<view class="today-focus">
</view>
</template>

<script>
	   export default {
	          data() {
	              return { itemFocus:[],
	             }
	         },
	         methods: {
	             },
				 }
</script>

<style>
.container {
 _height:500px;
}

.dd {
  color: #ff0909;
  font-family: '粗体';
  font-size: 88rpx;
}

.mm {
  font-size: 38rpx;
  text-align: center;
}

.cc {
  color: #02d7ff;
  font-size: 58rpx;
  text-align: center;
  margin-bottom: 16%;
  margin-top: 20%;
  flex-direction:column;
overflow: auto;
}

.user-motto {
  font-family: '黑体';
  font-size: 58rpx;
  text-align: center;
  margin-top:10%;

}

.today {
  font-size: 46rpx;
  text-align: center;
  margin-top:10%;
}

.ded {
  overflow: auto;
  _height: 1%;
}

</style>
