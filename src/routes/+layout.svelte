<script lang="ts">
	import '../app.css';
	import { ModeWatcher } from 'mode-watcher';

	import Navbar from '$lib/components/Navbar.svelte';
	import Footer from '$lib/components/Footer.svelte';

	let { children } = $props();
</script>

<ModeWatcher />
<Navbar />
{@render children()}
<Footer />
