<template>
	<div class="hello">
		<h1>{{ msg }}</h1>
	</div>
</template>

<script>
	export default {
		name: "HelloWorld",
		data() {
			return {
				msg: "Test Netlify App UPDATE!",
			};
		},
	};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
	h1 {
		font-weight: normal;
	}
</style>
