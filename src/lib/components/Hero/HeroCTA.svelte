<div class="flex flex-col-reverse gap-[54px] pb-5 md:flex-col md:gap-[36px] md:pb-0">
	<div class="flex w-full max-w-full flex-col gap-3 md:max-w-[313px]">
		<button class="cta-button"> GET STARTED → </button>
		<p class="cta-subtext">1-minute quiz for personalized Insights</p>
	</div>
	<div class="flex flex-col gap-[27px]">
		<p class="cta-terms">
			By clicking &quot;Get Started&quot;, you agree with Terms and Conditions, Privacy Policy,
			Subscription Terms
		</p>
		<p class="cta-copy">Fametonic 2025 © All Rights Reserved.</p>
	</div>
</div>

<style>
	@reference "../../../app.css";

	.cta-button {
		@apply h-[40px] w-full cursor-pointer rounded-[10px] bg-primary font-figtree text-xl leading-none font-bold drop-shadow-[2px_2px_10px_rgb(0,231,249)] transition-all duration-300 hover:bg-primary/90;
	}

	.cta-subtext {
		@apply text-center align-middle font-figtree text-[12px] leading-[16px] font-normal;
	}

	.cta-terms {
		@apply text-center align-middle font-figtree text-[12px] leading-none font-medium text-tertiary md:text-left;
	}

	.cta-copy {
		@apply text-center align-middle font-nunito text-[10px] leading-none font-medium text-tertiary md:text-left md:font-figtree;
	}
</style>
