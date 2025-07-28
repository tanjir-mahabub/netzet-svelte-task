<script lang="ts">
	import Banner from '$lib/components/Banner.svelte';
	import Header from '$lib/components/Header.svelte';
	import Hero from '$lib/components/Hero/Hero.svelte';
</script>

<main class="min-h-screen overflow-auto bg-dark text-white lg:overflow-hidden">
	<Banner />
	<article class="container mx-auto max-w-[960px]">
		<Header />
		<Hero />
	</article>
</main>
