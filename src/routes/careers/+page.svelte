<script lang="ts">
	// Component to display jobs
	import JobListing from '$lib/components/JobListing.svelte';

	// Import jobs (static)
	import { jobs } from '$lib/data/jobs';
</script>

<div class="md:content-margin mx-4 my-12 flex flex-col items-center gap-12">
	{#each jobs as job}
		<JobListing
			title={job.title}
			date={job.datePosted}
			description={job.description}
			location={job.location}
			link={job.link}
		/>
		<hr class=" w-[300px] border border-white" />
	{/each}
</div>
