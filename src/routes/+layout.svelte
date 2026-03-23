<script lang="ts">
	import './layout.css';
	import favicon from '$lib/assets/clippy.png';

	let { children } = $props();
</script>

<svelte:head><link rel="icon" href={favicon} /></svelte:head>
<a href="//hackclub.com">
	<img
		src="/flag-orpheus-left.svg"
		alt="Hack Club!"
		class="fixed top-8 -left-2 z-5000 w-32 rotate-12 transition-all hover:scale-120"
	/>
</a>
{@render children()}
