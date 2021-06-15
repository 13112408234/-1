<template>
	<view>
		
		<view class="u-flex user-box u-p-l-30 u-p-r-20 u-p-b-30 bgcolor">
			<view class="u-m-r-10">
				<u-avatar :src="pic" size="140"></u-avatar>
			</view>
			<view class="u-flex-1">
				<view class="u-font-18 u-p-b-20">善其身</view>
				
			</view>
			<view class="u-m-l-10 u-p-10">
				<u-icon name="arrow-right" color="#fff" size="28"></u-icon>
			</view>
		</view>
		
		<view class="u-m-t-20">
			<u-cell-group>
				<u-cell-item icon="rmb-circle" title="推广"></u-cell-item>
			</u-cell-group>
		</view>
		
		<view class="u-m-t-20">
			<u-cell-group>
				<u-cell-item icon="star" title="注册用户"></u-cell-item>
				<u-cell-item icon="photo" title="推广码"></u-cell-item>
				<u-cell-item icon="coupon" title="用户中心"></u-cell-item>
				<u-cell-item icon="download" title="下载app"></u-cell-item>
			</u-cell-group>
		</view>
		
		<view class="u-m-t-20">
			<u-cell-group>
				<u-cell-item icon="setting-fill" title="退出账号"></u-cell-item>
			</u-cell-group>
		</view>
	</view>
</template>

<script>
	export default {
		data() {
			return {
				pic:'http://6tt.co/2nn1i',
				show:true
			}
		},
		onLoad() {
			
		},
		methods: {
			
		}
	}
</script>

<style lang="scss">
page{
	background-color: #ededed;
}

.camera{
	width: 54px;
	height: 44px;
	
	&:active{
		background-color: #ededed;
	}
}
.user-box{
	background-color: #fff;
}
.bgcolor{
	background-color: #fa6a52;
   color: #fff;
   height: 100px;
}
</style>
