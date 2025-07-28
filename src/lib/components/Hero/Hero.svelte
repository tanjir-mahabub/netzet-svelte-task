<script lang="ts">
	import HeroHeading from './HeroHeading.svelte';
	import HeroFeatures from './HeroFeatures.svelte';
	import HeroCTA from './HeroCTA.svelte';
</script>

<section
	class="relative flex flex-col-reverse items-center justify-between gap-6 px-2 sm:px-6 md:flex-row md:py-[70px] xl:py-[30px]"
>
	<div class="z-10 max-w-[516px] flex-1 space-y-6 tracking-normal">
		<HeroHeading />
		<HeroFeatures />
		<HeroCTA />
	</div>

	<div
		class="pointer-events-none relative flex xl:block h-full mt-8 w-full flex-1 md:absolute md:-top-12 md:right-10 md:mt-0 md:h-full md:w-1/2"
	>
		<div class="relative mx-auto min-h-[250px] w-full md:min-h-[673px] xl:w-[666px]">
			<img src="/phone.png" alt="App Preview" class="h-full w-full object-contain" />
		</div>
	</div>
</section>
