<script>
	import StudentCard from './StudentCard.svelte';
</script>

<div class="p-5 w-1/4 flex flex-col h-full bg-white border-l border-gray-200">
	<h1 class="text-lg font-medium border-b border-gray-200 pb-3">Students (5)</h1>
	<div class="flex-1 mt-5 flex flex-col gap-3">
		{#each Array(5).fill(0) as _}
			<StudentCard />
		{/each}
	</div>
</div>
