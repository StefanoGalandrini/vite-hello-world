<script>
export default {
	data() {
		return {
			subtitle: "Jumbotron con Bootstrap",
			heroText: "Non sai cos'è un Jumbotron? Non sei l'unico!",
		};
	},
};
</script>

<template>
	<div class="jumbotron jumbotron-fluid">
		<div class="container-fluid">
			<h2 class="display-5">{{ subtitle }}</h2>
			<p class="lead">{{ heroText }}</p>
			<hr class="my-4" />

			<p class="lead">
				<a
					class="btn btn-success btn-lg"
					href="#"
					role="button"
					>OK</a
				>
			</p>
		</div>
	</div>
</template>

<style scoped>
.btn {
	padding: 0.5rem 3rem;
}
</style>
