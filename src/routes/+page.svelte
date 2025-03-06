<script lang="ts">
	import Button from '$lib/components/ui/button/button.svelte';
</script>

<div class="content-margin flex flex-col">
	<!-- Main Section -->
	<div class="mt-48 flex h-full w-full">
		<!-- Text -->
		<div class="mx-48 flex flex-col gap-2">
			<h1 class="font-normal">Do <span class="text-pink font-bold">more</span> with less.</h1>
			<h1 class="font-normal">
				Work on what <span class="text-pink font-bold">matters</span>, let
			</h1>
			<h1 class="font-normal">
				<span class="text-pink font-bold">us</span> tackle the problems.
			</h1>
			<Button
				class="font-josefin mt-12 w-56 rounded-md border-2 border-white bg-transparent py-7 text-2xl text-white hover:text-black"
				>Let’s Talk :D</Button
			>
		</div>

		<!-- Image -->
		<img
			src="logo-light-outline.png"
			class=" ml-[-320px] mt-[-80px] h-fit w-64 opacity-20"
			alt="Automatos Logo Outline"
		/>
	</div>

	<!-- Rest of the page -->
	<div id="middle" class="mt-32 h-screen pt-64">
		<div class="flex items-center justify-center">
			<!-- Text -->
			<div class="flex w-[900px] flex-col">
				<h1 class="">We do a lot of things.</h1>
				<p class="mr-52 mt-8 text-3xl">
					We’re an awesome team turning ideas into powerful digital solutions. Need a sleek web app,
					a rock-solid mobile app, or AI that actually works? We build it smart, scalable, and
					future-ready—so your business stays ahead, and we remain curious.
				</p>
			</div>

			<!-- Graphic -->
			<img src="green-diamonds.png" class="w-96" alt="" />
		</div>

		<!-- TODO -->
		<!-- 3 columns -->
	</div>
</div>
