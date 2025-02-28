<script lang="ts">
	import Button from '$lib/components/ui/button/button.svelte';
</script>

<div class="flex flex-col">
	<!-- Main Section -->
	<img id="home" class="h-screen object-cover" src="bg.png" alt="Website Background" />
	<div class="absolute left-0 top-0 mt-60 flex h-full w-full flex-col items-center gap-4">
		<!-- Your Overlay Content -->
		<h1 class="font-light">Do <span class="font-bold">more</span> with less.</h1>
		<h1 class="font-light">Work on what <span class="font-bold">matters</span>,</h1>
		<h1 class="font-light">Let <span class="font-bold">us</span> tackle the problems.</h1>

		<Button
			class="mt-12 bg-white/20 p-8 text-3xl text-white shadow-lg backdrop-blur-md hover:text-black"
			>Let’s Talk 🥳</Button
		>
	</div>

	<!-- Rest of the page -->
	<div
		id="middle"
		class="h-screen bg-gradient-to-br from-[#0F0917] via-[#170417] to-[#170417] px-44 pt-12"
	>
		<h3 class="">We do a lot of things.</h3>
		<p class="mr-96 mt-8 text-3xl">
			We’re an awesome team turning ideas into powerful digital solutions. Need a sleek web app, a
			rock-solid mobile app, or AI that actually works? We build it smart, scalable, and
			future-ready—so your business stays ahead, and we remain curious.
		</p>

		<!-- TODO -->
		<!-- 3 columns -->
	</div>
</div>
