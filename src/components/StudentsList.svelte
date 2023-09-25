<script>
	import StudentCard from './StudentCard.svelte';
	export let rowSmall = false;
</script>

<div
	class="h-full w-full {rowSmall
		? 'p-0 py-4 flex flex-col'
		: 'bg-white border-l border-gray-200 p-5 flex flex-col'}"
>
	<h1
		class="text-lg font-medium border-b border-gray-200 pb-3 {rowSmall
			? 'flex items-center justify-between'
			: ''}"
	>
		Students (5) {#if rowSmall}<span class="text-sm text-blue-500">Show More</span>{/if}
	</h1>
	<div class="mt-5 flex gap-3 {rowSmall ? 'flex-row overflow-y-scroll' : 'flex-col flex-1'}">
		{#each Array(5).fill(0) as _}
			<StudentCard small={rowSmall} />
		{/each}
	</div>
</div>
