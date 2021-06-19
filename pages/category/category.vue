<template>
		<view>
			<!-- 顶部 -->
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
						  <text>健康商城</text>
						 </view>
					</view>
					<view>
						 <u-avatar :src="src" mode="square"></u-avatar>
						 <view style="margin-top: 25rpx;">
						  <text>健康课堂</text>
						 </view>
					</view>
				</view>
			</view>
			<!-- 就近医 -->
			<view class="jjyi">
				<view>
					<text class="text1">就近医</text>
					<text>更多></text>
				</view>
				<view class="jjyi1">
					<view>
						 <u-avatar :src="src" mode="square"></u-avatar>
						 <view style="margin-top: 25rpx;">
							 <text>某某某某某医院</text>
						 </view>
					</view>
					<view>
						 <u-avatar :src="src" mode="square"></u-avatar>
						 <view style="margin-top: 25rpx;">
						  <text>某某某某某医院</text>
						 </view>
					</view>
					<view>
						 <u-avatar :src="src" mode="square"></u-avatar>
						 <view style="margin-top: 25rpx;">
						  <text>某某某某某医院</text>
						 </view>
					</view>
				</view>
			</view>
			<!-- 附近医药 -->
			<view class="jjyi jjyicolor">
				<view>
					<text class="text1">附近药房</text>
					<text>更多></text>
				</view>
				<view class="jjyi1">
					<view>
						 <u-avatar :src="src" mode="square"></u-avatar>
						 <view style="margin-top: 25rpx;">
							 <text>某某某某某医院</text>
						 </view>
					</view>
					<view>
						 <u-avatar :src="src" mode="square"></u-avatar>
						 <view style="margin-top: 25rpx;">
						  <text>某某某某某医院</text>
						 </view>
					</view>
					<view>
						 <u-avatar :src="src" mode="square"></u-avatar>
						 <view style="margin-top: 25rpx;">
						  <text>某某某某某医院</text>
						 </view>
					</view>
				</view>
			</view>
			<!-- 找对医生 -->
			<view class="jjyi jjyicolor2">
				<view>
					<text class="text1">找对医生</text>
					<text>更多></text>
				</view>
				<view class="jjyi1">
					<view>
						 <u-avatar :src="src" mode="square"></u-avatar>
						 <view style="margin-top: 25rpx;">
							 <text>某某某某某医院</text>
						 </view>
					</view>
					<view>
						 <u-avatar :src="src" mode="square"></u-avatar>
						 <view style="margin-top: 25rpx;">
						  <text>某某某某某医院</text>
						 </view>
					</view>
					<view>
						 <u-avatar :src="src" mode="square"></u-avatar>
						 <view style="margin-top: 25rpx;">
						  <text>某某某某某医院</text>
						 </view>
					</view>
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
	
</style>
