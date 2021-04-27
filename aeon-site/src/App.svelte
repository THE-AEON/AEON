<script lang="ts">
	export let name: string = 'ÆON';
</script>

<main>
	<h1>{name.toUpperCase()}</h1>
</main>

<style>
	main {
		text-align: center;
		padding: 0.1em;
		max-width: 240px;
		margin: 0 auto;
	}

	h1 {
		color: #ffa900;
		font-size: 4em;
		font-weight: 100;
	}

	@media (min-width: 640px) {
		main {
			max-width: none;
		}
	}
</style>