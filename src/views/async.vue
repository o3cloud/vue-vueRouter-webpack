<template>
<p>
	async
</p>
</template>

<script>
	require('../css/b.css');
	module.exports = {
		//props: ['父组建传的值'],
		data:function(){
			return {
				title:'async'
			}
		},
		ready:function(){
			this.$root.$set('header',this.title)
		}
	}
</script>