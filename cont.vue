<template>
	<div class="content">
		<p>{{tip}}</p>
	</div>
</template>

<script>
	export default{
		name:"cont",
		data(){
			return {
				tip:"我是中间部分"
			}
		}
		
	}
</script>

<style scoped>
	.content{
		height: 500px;
		width: 100%;
		background: yellow;
	}
</style>