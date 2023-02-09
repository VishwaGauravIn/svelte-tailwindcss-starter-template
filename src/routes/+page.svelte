<script>
	let clickCount = 0;
	const onClickFun = () => {
		clickCount++;
	};
</script>

<h1>Welcome to SvelteKit Starter Template superpowered by TailwindCSS</h1>
<p>Visit <a href="https://kit.svelte.dev">kit.svelte.dev</a> to read the documentation</p>

<button class="bg-yellow-200 text-yellow-900 px-6 py-2 font-semibold m-4" on:click={onClickFun}
	>Click Me</button
>
{clickCount}
