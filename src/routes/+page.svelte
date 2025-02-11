<script lang="ts">
	import Button from '$lib/components/ui/button/button.svelte';
</script>

<div class="flex flex-col">
	<!-- Main Section -->
	<img id="home" class="h-screen object-cover" src="bg.png" alt="Website Background" />
	<div class="absolute left-0 top-0 mt-60 flex h-full w-full flex-col items-center gap-4">
		<!-- Your Overlay Content -->
		<h1 class="text-7xl font-light">Do <span class="font-bold">more</span> with less.</h1>
		<h1 class="text-7xl font-light">Work on what <span class="font-bold">matters</span>,</h1>
		<h1 class="text-7xl font-light">Let <span class="font-bold">us</span> tackle the problems.</h1>

		<Button
			class="mt-12 bg-white/20 p-8 text-3xl text-white shadow-lg backdrop-blur-md hover:text-black"
			>Let’s Talk 🥳</Button
		>
	</div>

	<!-- Rest of the page -->
	<div id="middle" class="h-screen bg-gradient-to-br from-[#0F0917] via-[#170417] to-[#170417]">
		<h1>Yep</h1>
	</div>
</div>
