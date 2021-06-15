<template>
	<view class="wrap">
		<!-- 轮播图 -->
		<u-swiper :list="list" height="250rpx"></u-swiper>
		<u-row gutter="16" >
			<u-col span="3" text-align="center">123</u-col>
			<u-col span="3">123</u-col>
			<u-col span="3">123</u-col>
			<u-col span="3">123</u-col>
		</u-row>
	</view>
</template>

<script>
	export default {
		data() {
			return {
				list: [{
						image: 'https://cdn.uviewui.com/uview/swiper/1.jpg',
					},
					{
						image: 'https://cdn.uviewui.com/uview/swiper/2.jpg',
					},
					{
						image: 'https://cdn.uviewui.com/uview/swiper/3.jpg',
					}
				],
			}
		},
		methods: {

		}
	}
</script>

<style lang="scss" scoped>
	.wrap {
		padding: 40rpx;
	}
</style>