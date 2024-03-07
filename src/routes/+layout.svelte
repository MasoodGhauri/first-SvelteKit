<script>
	import Title from '$lib/pageTitle.svelte';
</script>

<header>
	<Title title="About" />
</header>
<main>
	<!-- all children will be displayed in it automaticlly -->
	<slot />
</main>

<footer>Copyrights - Bragging House</footer>
