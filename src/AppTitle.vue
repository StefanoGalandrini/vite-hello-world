<script>
export default {
	data() {
		return {
			title: "La mia prima volta con Vite!",
		};
	},
};
</script>

<template>
	<h1 class="title">{{ title }}</h1>
</template>

<style scoped>
.title {
	font-size: 4rem;
	font-weight: 700;
	color: rgb(127, 32, 158);
	margin-bottom: 8rem;
}
</style>
