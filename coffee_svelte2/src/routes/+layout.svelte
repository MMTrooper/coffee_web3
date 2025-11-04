<script>
	import '../app.css';
	import favicon from '$lib/assets/favicon.svg';

	let { children } = $props();
</script>

<svelte:head>
	<link rel="icon" href={favicon} />
</svelte:head>

{@render children()}

<Footer />

<!-- header
hero
product description
mission in place of reviews
services in place of faq
contact in place of conversion
footer -->
