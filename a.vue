<template>
	<div class="a">
		
	    {{count}}
		<button @click="increment">点击我加1</button>
		<button @click="decrement">点击我减1</button>
		<Table></Table>
	</div>
</template>

<script>
	import Vue from 'vue';
	import Table from './table/table'
	export default{
		data(){
			return {
				
			}
		},
		components:{
			Table
		},
		methods:{
			increment(){
				this.$store.commit("increment")
			},
			decrement(){
				this.$store.commit("decrement")
			}
		},
		 computed:{
            count(){
                return this.$store.state.count
            },
        }
	}
</script>

<style>
 .a{
 	height: 100px;
 	width: 100%;

 }
</style>