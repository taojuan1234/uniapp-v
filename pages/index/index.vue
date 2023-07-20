<template>
	<view class="content">
		<h2>测试功能</h2>
		<div class="content">哈哈哈哈哈哈哈 <span class="spans">oooo</span></div>
		<navigator url="/pages/demo/demo" open-type="switchTab">详情页面</navigator>
	</view>
</template>

<script>
	export default {
		data() {
			return {
				title: 'Hello'
			}
		},
		onLoad() {

		},
		methods: {

		}
	}
</script>

<style lang='scss'>
	.content {
		height: 100px;
		width: 100px;

		.spans {
			color: red;
		}
	}
</style>