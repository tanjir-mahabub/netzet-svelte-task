<section class="bg-gradient-primary-secondary h-full w-full py-2 xs:h-[76px] xs:py-0 lg:h-[46px]">
	<div class="container mx-auto flex h-full w-fit max-w-[960px] items-center justify-center px-3">
		<div
			class="flex max-w-[350px] items-start text-center sm:max-w-[500px] md:max-w-fit md:text-left lg:gap-1"
		>
			<span class="banner-emoji">🚀</span>
			<p class="banner-text">
				<span class="font-extrabold text-[#00E7F9]">FRESH BEGINNINGS SALE:</span>
				<span class="font-semibold"> Extra 25% OFF, Limited Spots - start your journey today!</span>
			</p>
		</div>
	</div>
</section>

<style>
	@reference "../../app.css";

	.bg-gradient-primary-secondary {
		background-image: var(--gradient-primary-secondary);
	}
	.banner-emoji {
		@apply flex-shrink-0 text-center font-figtree text-[16px] leading-none font-extrabold md:text-right lg:text-[22px];
	}
	.banner-text {
		@apply text-center font-figtree text-[16px] leading-none text-white sm:text-[18px] md:text-left xl:text-[22px] tracking-wide;
	}
</style>
