<template>
	<div>
		<div class="card">
			<img
				:src="image"
				alt="dodici immagini di copertine della serie fumetti DC Comics"
			/>
			<h4>{{ title }}</h4>
		</div>
	</div>
</template>

<script>
export default {
	props: {
		image: String,
		title: String,
	},
};
</script>

<style lang="scss">
.card {
	color: #fff;
	text-align: left;
	&:hover {
		cursor: pointer;
	}
	h4 {
		padding: 0.5rem;
	}
}
</style>
