<template>
  <div class="hello">
    <p>{{msg}}</p>
   
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  data () {
    return {
      msg: '我是vue的头部'
    }
  }
  
}

</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
	.hello{
		height: 300px;
		width: 100%;
		background: aqua;
	}
</style>
