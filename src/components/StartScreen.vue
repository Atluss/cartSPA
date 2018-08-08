<template>
	<div class="alert alert-secondary">
		<h3>Are you ready?</h3>
		<button class="btn btn-success" v-on:click="$emit('onStart')">Start</button>
	</div>
</template>

<script>
	export default {

	}
</script>

<style scoped>
	
</style>