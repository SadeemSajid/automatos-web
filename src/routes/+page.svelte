<script lang="ts">
	import Button from '$lib/components/ui/button/button.svelte';
</script>

<div class="md:content-margin mx-4 flex flex-col items-center">
	<!-- Main Section -->
	<div class="mt-48 flex h-full w-fit lg:mr-20">
		<!-- Text -->
		<div class="flex flex-col gap-2 md:mx-48">
			<h1 class="font-normal">Do <span class="text-pink font-bold">more</span> with less.</h1>
			<h1 class="font-normal">
				Work on what <span class="text-pink font-bold">matters</span>,
			</h1>
			<h1 class="font-normal">
				Let <span class="text-pink font-bold">us</span> tackle the problems.
			</h1>
		</div>

		<!-- Image -->
		<img
			src="logo-light-outline.png"
			class=" ml-[-250px] mt-[-120px] h-fit w-56 opacity-20 md:ml-[-320px] md:mt-[-80px] md:w-64"
			alt="Automatos Logo Outline"
		/>
	</div>

	<!-- Rest of the page -->
	<div id="middle" class="mt-32 h-screen pt-20 lg:pt-64">
		<div class="flex flex-col items-center justify-center lg:flex-row">
			<!-- Text -->
			<div class="flex flex-col lg:w-[800px]">
				<h1 class="">We do a lot of things.</h1>
				<p class="mt-8 text-3xl lg:mr-52">
					We’re an awesome team turning ideas into powerful digital solutions. Need a sleek web app,
					a rock-solid mobile app, or AI that actually works? We build it smart, scalable, and
					future-ready—so your business stays ahead, and we remain curious.
				</p>
			</div>

			<!-- Graphic -->
			<img src="green-diamonds.png" class="mt-12 w-48 lg:mt-0 lg:w-96" alt="" />
		</div>

		<!-- TODO -->
		<!-- 3 columns -->
	</div>

	<div id="services" class="mb-96 mt-48 flex flex-col items-center justify-center lg:mt-12">
		<h2 class="mb-12 text-5xl">Some Cool Tech :)</h2>
		<img src="tech.png" class="w-[500px]" alt="" />
	</div>
</div>
