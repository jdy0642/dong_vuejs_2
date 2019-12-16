<template>
	<div>
		<Nav></Nav>
	</div>
</template>	
<script>
import Nav from '@/components/Nav.vue'
export default{
	name: 'home',
	components : {
		Nav
	},
	data(){
		return {
			msg : '홈화면으로 들어옴 !!'
		}
	}
}
</script>
<style scoped></style>