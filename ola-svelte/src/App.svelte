<script lang="ts">
import Calculadora from "./components/Calculadora.svelte";
	
</script>

<main>
	<Calculadora />
</main>

<style>
	:global(body) {
		background-color: black;
	}

	:root {
		--cor-fundo: #555;
	}

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