<template>
	<div class="b">
		{{age}}
		<p>我是i</p>

	<slot  name=”header”>sdddddddddddddd</slot>

	<slot  name=”main”>d</slot>
	
	<slot  name=”footer”></slot>
	
	<slot  name=”other”></slot>
	</div>
</template>

<script>
	export default{
		data(){
			return {
				
				age:65,
				
				
			}
			
		}
	}
</script>

<style>
	 .b{
 	height: 100px;
 	width: 100%;
 	background: #eee;

 }
</style>