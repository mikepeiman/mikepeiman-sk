

<script>
	import { EvervaultCard, Icon } from '../components/ui/EvervaultCard/index.ts';
</script>

<div
	class="relative mx-auto flex h-full w-full flex-col items-start"
>
	<Icon class="absolute -left-3 -top-3 h-6 w-6 text-black dark:text-white" />
	<Icon class="absolute -bottom-3 -left-3 h-6 w-6 text-black dark:text-white" />
	<Icon class="absolute -right-3 -top-3 h-6 w-6 text-black dark:text-white" />
	<Icon class="absolute -bottom-3 -right-3 h-6 w-6 text-black dark:text-white" />

	<EvervaultCard text="" />

	<!-- <h2 class="mt-4 text-sm font-light text-black dark:text-white">
		Hover over this card to reveal an awesome effect. Running out of copy here.
	</h2> -->
	<!-- <p
		class="mt-4 rounded-full border border-black/[0.2] px-2 py-0.5 text-sm font-light text-black dark:border-white/[0.2] dark:text-white"
	>
		Watch me hover
	</p> -->
</div>
<style lang="postcss">
	:global(html) {
		background-color: theme(colors.gray.100);
		background-image: url(dall-e3-mosaic-bento-bg-0.jpg);
		background-repeat: no-repeat;
		background-attachment: fixed;
		background-size: cover;
	}
</style>
