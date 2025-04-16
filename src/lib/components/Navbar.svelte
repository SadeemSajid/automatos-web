<script lang="ts">
	import { goto } from '$app/navigation';

	function scroll(id: string) {
		goto(`/#${id}`).then(() => {
			// wait for DOM update
			setTimeout(() => {
				document.getElementById(id)?.scrollIntoView({
					behavior: 'smooth',
					block: 'center'
				});
			}, 100);
		});
	}
</script>

<header class="mt-8 flex w-full flex-col items-center justify-between py-8">
	<a href="/"><h2 class="mb-4 text-xl font-bold">AUTOMATOS.</h2></a>
	<div class="flex gap-8">
		<a href="/" on:click={() => scroll('middle')}><p>About</p></a>
		<a href="/" on:click={() => scroll('services')}><p>Tech</p></a>
		<a href="/" on:click={() => scroll('middle')}><p>Services</p></a>
		<a href="/careers"><p>Careers</p></a>
	</div>
</header>
