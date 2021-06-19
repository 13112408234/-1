<template>
		<view>
			<!-- 导航栏 -->
			<view class="jjyi dbu1">
				<view class="jjyi1">
					<view>
						 <u-avatar :src="src" mode="square"></u-avatar>
						 <view style="margin-top: 25rpx;">
							 <text>养生视频</text>
						 </view>
					</view>
					<view>
						 <u-avatar :src="src" mode="square"></u-avatar>
						 <view style="margin-top: 25rpx;">
							 <text>健康中心</text>
						 </view>
					</view>
					<view>
						 <u-avatar :src="src" mode="square"></u-avatar>
						 <view style="margin-top: 25rpx;">
						  <text>养生知识</text>
						 </view>
					</view>
					<view>
						 <u-avatar :src="src" mode="square"></u-avatar>
						 <view style="margin-top: 25rpx;">
						  <text>养生论坛</text>
						 </view>
					</view>
				</view>
			</view>
			<!-- 健康体测部分 -->
			<view class="jian">
					<text class="jiance">健康体检</text>
					<view class="jian1">
						<text>
								<text>应用健康体检软件，可以减少个体大病发生的概率</text>
								<text>通过其他特色功能向用户提供健康方面的帮助，</text>
								<text>完成测试后，您将了解到您的体质详情，并获得相</text>
								<text>应的个性化解决方法。</text>
						</text>
					</view>
					<!-- 检测按钮 -->
					<view class="jianann">
						<u-button type="primary" size="medium">开始体检</u-button>
					</view>
			</view>
			<!-- 文章部分 -->
		
					<view class="wenzhan">
						<view class="wenz">
							<text>身体健康的标准</text>
							<view>身体健康的标准一、关于健康的定义：“健康乃是一种在身体上、精神上的完满状态、以及良好的适应力</view>
							<text class="text10">
								<text>跟新时间：2018-03-06 来源：[原创]</text>
							</text>
						</view>
						<view class="wenz">
							<text>身体健康的标准</text>
							<view>身体健康的标准一、关于健康的定义：“健康乃是一种在身体上、精神上的完满状态、以及良好的适应力</view>
							<text class="text10">
								<text>跟新时间：2018-03-06 来源：[原创]</text>
							</text>
						</view>
						<view class="wenz">
							<text>身体健康的标准</text>
							<view>身体健康的标准一、关于健康的定义：“健康乃是一种在身体上、精神上的完满状态、以及良好的适应力</view>
							<text class="text10">
								<text>跟新时间：2018-03-06 来源：[原创]</text>
							</text>
						</view>
						<view class="wenz">
							<text>身体健康的标准</text>
							<view>身体健康的标准一、关于健康的定义：“健康乃是一种在身体上、精神上的完满状态、以及良好的适应力</view>
							<text class="text10">
								<text>跟新时间：2018-03-06 来源：[原创]</text>
							</text>
						</view>
				</view>
		</view>
</template>

<script>
export default {
	data() {
			return {
				src: ''
			}
		}
	
};
</script>

<style scoped lang="scss">
	.jjyi{
		margin: 25rpx;
		padding: 25rpx;
		background-color: rgb(255,248,235);
		height: 400rpx;
	}
	.jjyi>view{
		display: flex;
		justify-content: space-between;
		align-items: center; 
	
	}
	.jjyi>view>text{
		line-height: 50rpx;
		color: rgb(179,147,113);
	}
	.text1{
	  font-size: 50rpx;
	  color: rgb(162,124,85);
	}
	.jjyi1>view{
		padding-top:50rpx;
		display: inline-block;
		text-align: center;
		width:33.3%;
	}
	.jjyicolor{
		background-color: rgb(242,247,255);
	}
	.jjyicolor>view>text{
		line-height: 50rpx;
		color: #000;
	}
	.jjyicolor2{
		background-color: rgb(255,246,242);
	}
	.jjyicolor2>view>text{
		line-height: 50rpx;
		color: rgb(128,91,67);
	}
	.dbu1{
		background-color: #fff;
		height:350rpx;
	}
	.jiance{
		display: flex;
		justify-content: center;
		font-size: 40rpx;
		margin-bottom: 45rpx;;
	}
	.jian1{
		margin-left: 35rpx;
		font-size: 30rpx;
		margin-right: 30px;
	}
	.jian1 text{
		line-height: 60rpx;
	}
	.jianann{
		display: flex;
		justify-content: center;
		margin-top: 100rpx;
	}
	.wenz {
		margin-top: 30rpx;
		height: 200rpx;
		background-color: #fff;
		view{
			color: #747474;
			
		}
		padding-left: 35rpx;
		padding-top: 20rpx;
		background-color: #fff;
	}
	.text10{
		display: flex;
		justify-content: flex-end;
		font-size: 22rpx;
		color: #c4c4c4;
		padding-top: 20rpx;
	}
	.wenzhan {
		background-color: #f5f5f5;
	}
</style>
