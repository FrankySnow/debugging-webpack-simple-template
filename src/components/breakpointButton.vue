<template>  
	<button class="breakpointButton" @click="triggerBreakpoint">breakpoint</button>
</template>

<script>
export default {
	methods:{
		triggerBreakpoint(e){
			console.log(e)
		}
	}
}
</script>

<style>
.breakpointButton {
	background: #41b883;
	padding: 1em;
	border: none;
	color: #35495e;
	font-weight: bold;
	cursor: pointer;
	border: 1px solid #35495e;
	border-left: 0;
}

.breakpointButton:hover {
	background: #35495e;
	color: white;
}
</style>