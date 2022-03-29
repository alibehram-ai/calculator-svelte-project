<script lang="ts">
	import Header from './Components/Header/header.svelte';
	import Calculator from './Components/Calculator/calculator.svelte';
	
	
	export let name: string;
</script>

<main>
	<Header />

	<Calculator />
</main>

<style>
	main {
		text-align: center;
		padding: 1em;
		max-width: 240px;
		margin: 0 auto;
	}

	

	@media (min-width: 640px) {
		main {
			max-width: none;
		}
	}
</style>