<script lang="ts">
	function scroll(id: string) {
		document.getElementById(id)?.scrollIntoView({ behavior: 'smooth', block: 'center' });
	}
</script>

<header class="absolute flex w-full items-center justify-between py-8">
	<img src="logo-white.png" class="ml-44 w-12" alt="Automatos Logo" />
	<div class="mr-44 flex gap-8">
		<a href="#home" on:click={() => scroll('home')}><p>Home</p></a>
		<a href="#home" on:click={() => scroll('middle')}><p>Services</p></a>
		<a href="#home" on:click={() => scroll('home')}><p>Portfolio</p></a>
	</div>
</header>
