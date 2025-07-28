<script lang="ts">
	import FeatureItem from './FeatureItem.svelte';
	const features = [
		'Start growing your influence right away—no waiting required!',
		'Create viral TikToks and Reels step by step with easy-to-follow lessons',
		'Use a Personal AI Worker to boost your content',
		'Learn from expert-led courses designed for aspiring influencers'
	];
</script>

<ul class="space-y-3 font-figtree text-[16px] leading-[22px] font-normal lg:font-semibold">
	{#each features as feature}
		<FeatureItem text={feature} />
	{/each}
</ul>
