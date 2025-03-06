<script lang="ts">
	function scroll(id: string) {
		document.getElementById(id)?.scrollIntoView({ behavior: 'smooth', block: 'center' });
	}
</script>

<header class="mt-8 flex w-full flex-col items-center justify-between py-8">
	<h2 class="mb-4 text-xl font-bold">AUTOMATOS.</h2>
	<div class="flex gap-8">
		<a href="#home" on:click={() => scroll('home')}><p>Services</p></a>
		<a href="#home" on:click={() => scroll('middle')}><p>Products</p></a>
		<a href="#home" on:click={() => scroll('middle')}><p>Portfolio</p></a>
	</div>
</header>
