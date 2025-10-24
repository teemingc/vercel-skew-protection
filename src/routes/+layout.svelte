<script lang="ts">
	import favicon from '$lib/assets/favicon.svg';

	let { children } = $props();
</script>

<svelte:head>
	<link rel="icon" href={favicon} />
</svelte:head>

<ul>
	<li><a href="/">home page</a></li>
	<li><a href="/about">about page</a></li>
</ul>

{@render children?.()}
