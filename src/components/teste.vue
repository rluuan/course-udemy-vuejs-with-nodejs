<template>
	<h1> {{ titulo }} </h1>
</template>

<script>
	export default {
		props: ['titulo']
	}

</script>

<style>
	h1 {
		color: red;
	}
</style>