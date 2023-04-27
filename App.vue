<script>
	export default {
		onLaunch: function() {
			console.log('App Launch')
		},
		onShow: function() {
			console.log('App Show')
		},
		onHide: function() {
			console.log('App Hide')
		}
	}
</script>

<style lang="scss">
	/*每个页面公共css */
	
	/*引入uview基础样式*/
	@import '@/uni_modules/uview-ui/index.scss';
	
	/*引入icon图标库*/
	@import url("static/icon/iconfont.css");
</style>
