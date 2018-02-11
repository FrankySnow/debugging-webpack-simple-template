<template>  
	<button class="exceptionButton" @click="triggerException">exception</button>
</template>

<script>
export default {
	methods:{
		triggerException(){
			myUndefinedFunction()
		}
	}
}
</script>

<style>
.exceptionButton {
	background: #41b883;
	padding: 1em;
	border: none;
	color: #35495e;
	font-weight: bold;
	cursor: pointer;
	border: 1px solid #35495e;
}

.exceptionButton:hover {
	background: #35495e;
	color: white;
}
</style>