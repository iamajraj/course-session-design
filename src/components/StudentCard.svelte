<script lang="ts">
	export let small = false;
</script>

<div
	class="w-full border border-gray-200 rounded-lg py-2 flex items-center gap-5 transition-all hover:border-gray-400 cursor-pointer relative {small
		? 'w-10 h-16'
		: 'px-2'}"
>
	<img
		src="https://api.dicebear.com/7.x/avataaars/svg?seed=Bella"
		alt="user"
		class="{small ? 'w-full h-full' : 'w-10 h-10'} rounded-full"
	/>
	{#if !small} <p class="font-light">Akmal Hossain Raj</p>{/if}
	<div
		class="absolute w-3 h-3 rounded-full bg-green-400 {small
			? 'top-0 right-0'
			: 'right-4 animate-pulse'}"
	/>
</div>
