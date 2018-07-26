<template>
	<div class="footer">
		<p>{{tip}}</p>
	</div>
</template>

<script>
	export  default {
		name:"footers",
		data(){
			return {
				tip:"我是vue的底部"
			}
		}
		
	}
</script>

<style scoped="scoped">
.footer{
	height: 200px;
	background: red;
}
</style>