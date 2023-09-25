<script>
	import Countdown from './Countdown.svelte';
	import Loader from './Loader.svelte';
	import StudentsList from './StudentsList.svelte';
</script>

<div class="flex-1 p-4 md:p-10 flex flex-col md:flex-row">
	<div class="bg-white p-4 md:p-10 flex flex-col md:flex-row rounded-lg">
		<div class="w-full md:w-[60%] shrink-0">
			<div
				class="aspect-video md:aspect-auto h-[200px] md:h-[300px] rounded-lg border bg-gray-100 flex items-center justify-center relative overflow-hidden"
			>
				<h1 class="absolute text-[170px] md:text-[300px] text-gray-200">LIVE</h1>
				<Loader />
			</div>
			<h2 class="text-2xl border-b pb-3 mt-5">
				Title: <span class="font-medium">Code with a cup of <s>coffee</s></span>
			</h2>
			<p class="text-sm mt-2 text-gray-500">
				Something which sucks not always the same thing that sucks, sometimes we need to look back
				and see what we left, well am I really talking about coding nah?? Oops I miss the track well
				no problem its fine let's move to coding and stop thinking about everything but ofcourse
				don't remember the one who created you, fullfill his duties and let's do coding
			</p>
			<div class="block md:hidden">
				<StudentsList rowSmall={true} />
			</div>
		</div>
		<div class="flex flex-col gap-4 mt-5 md:mt-0 pt-5 md:pt-0 border-t md:border-none">
			<p class="flex items-center gap-4 self-center">
				Share the Link <svg
					xmlns="http://www.w3.org/2000/svg"
					fill="none"
					viewBox="0 0 24 24"
					stroke-width="1.5"
					stroke="currentColor"
					class="w-6 h-6 cursor-pointer hover:scale-110 transition-all"
				>
					<path
						stroke-linecap="round"
						stroke-linejoin="round"
						d="M13.19 8.688a4.5 4.5 0 011.242 7.244l-4.5 4.5a4.5 4.5 0 01-6.364-6.364l1.757-1.757m13.35-.622l1.757-1.757a4.5 4.5 0 00-6.364-6.364l-4.5 4.5a4.5 4.5 0 001.242 7.244"
					/>
				</svg>
			</p>
			<img src="/qr-code.svg" alt="qr" class="w-full h-[300px] aspect-video object-contain" />
			<div class="flex flex-col items-center gap-3">
				<p>Session starts at:</p>
				<Countdown />
			</div>
		</div>
	</div>
</div>
