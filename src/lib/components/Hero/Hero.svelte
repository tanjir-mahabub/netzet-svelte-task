<script lang="ts">
	import HeroHeading from './HeroHeading.svelte';
	import HeroFeatures from './HeroFeatures.svelte';
	import HeroCTA from './HeroCTA.svelte';
</script>

<section
	class="relative flex flex-col-reverse items-center justify-between sm:gap-6 px-2 sm:px-8 md:flex-row md:py-[70px] xl:py-[44px]"
>
	<div class="z-10 max-w-[516px] flex-1 tracking-normal -top-[22px] sm:top-0 relative">
		<HeroHeading />
		<HeroFeatures />
		<HeroCTA />
	</div>

	<div
		class="pointer-events-none relative flex h-auto w-full flex-1 md:absolute md:-top-[33px] md:right-[47px] md:mt-0 md:h-full md:w-1/2 xl:block"
	>
		<div class="relative -top-[10px] mx-auto h-[310px] sm:h-full w-full md:min-h-[673px] xl:w-[666px]">
			<img src="/phone.png" alt="App Preview" class="h-full sm:h-full w-full object-contain" />
		</div>
	</div>
</section>
