<script>
	let message = 'Hello World';
    
	let counter = 0;

	function increment_counter() {
		counter++;
	}

	function reset_counter() {
		counter = 0;
	}
</script>

<h2>Home Page - {message}</h2>
<p> </p>
<p>Visit <a href="https://kit.svelte.dev">kit.svelte.dev</a> to read the documentation</p>

<h3>Counter value: <input bind:value={counter} type="text" /></h3>

<button on:click={increment_counter}>Increment</button>
<button on:click={reset_counter}>Reset</button>
