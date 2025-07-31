<div class="flex flex-col-reverse gap-[40px] pb-5 md:flex-col md:gap-[28px] md:pb-0 mt-4 sm:mt-8">
	<div class="flex w-full max-w-full flex-col gap-2.5 md:max-w-[313px]">
		<button class="cta-button"> GET STARTED 		
			<svg width="8" height="14" viewBox="0 0 8 14" fill="none" xmlns="http://www.w3.org/2000/svg">
			<path d="M7.19238 6.26465C7.60266 6.67918 7.60225 7.33287 7.19141 7.74707L2.29102 12.6875C1.87768 13.1039 1.22189 13.104 0.808594 12.6875C0.607462 12.4847 0.50002 12.2157 0.5 11.9512L0.5 11.7451L0.538086 11.707C0.551454 11.6485 0.568204 11.5907 0.591797 11.5352C0.644656 11.4108 0.722378 11.2983 0.819336 11.2041L4.97949 7L0.818359 2.7959L0.819336 2.79492C0.408805 2.3804 0.4084 1.72679 0.819336 1.3125C1.23271 0.895833 1.88939 0.895784 2.30273 1.3125L2.30273 1.31348L7.19238 6.26465Z" fill="white" stroke="white"/>
			</svg>	
		</button>
		<p class="cta-subtext">1-minute quiz for personalized Insights</p>
	</div>
	<div class="flex flex-col gap-[15px] sm:gap-[16px] px-5 sm:px-0">
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
		@apply h-[40px] w-full flex justify-center items-center gap-2 cursor-pointer rounded-[10px] bg-primary font-figtree text-xl leading-none font-bold drop-shadow-[2px_2px_10px_rgb(0,231,249)] transition-all duration-300 hover:bg-primary/90;
	}

	.cta-subtext {
		@apply text-center align-middle font-figtree text-[12px] leading-[16px] font-normal;
	}

	.cta-terms {
		@apply text-center align-middle font-figtree text-[12px] leading-[14px] font-medium text-tertiary md:text-left;
	}

	.cta-copy {
		@apply text-center align-middle font-nunito text-[10px] leading-none font-medium text-tertiary md:text-left md:font-figtree;
	}
</style>
