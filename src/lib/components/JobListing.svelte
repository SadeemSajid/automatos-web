<script lang="ts">
	export let title = '';
	export let location = '';
	export let date = '';
	export let description = '';
	export let link = '';
</script>

<div class="flex max-w-[600px] flex-col gap-4">
	<a href={link} class="hover:text-[#DFB6BE]"><h1>{title}.</h1></a>
	<div class="flex items-baseline gap-16">
		<p class="text-2xl">{location}</p>
		<p class="text-white/50">{date}</p>
	</div>
	<p class="mt-4 text-xl">{description}</p>
</div>
