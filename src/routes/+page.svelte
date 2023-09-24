<script>
	import Loader from '../components/Loader.svelte';
</script>

<div class="w-full h-full flex">
	<div class="flex flex-col py-5 px-10 w-1/6 h-full shadow-lg border-r border-gray-200">
		<h1 class="text-2xl font-bold flex items-center justify-between">
			SESSiON
			<svg
				xmlns="http://www.w3.org/2000/svg"
				fill="none"
				viewBox="0 0 24 24"
				stroke-width="1.5"
				stroke="currentColor"
				class="w-6 h-6"
			>
				<path
					stroke-linecap="round"
					stroke-linejoin="round"
					d="M3.75 6.75h16.5M3.75 12H12m-8.25 5.25h16.5"
				/>
			</svg>
		</h1>

		<ul class="mt-16 flex flex-col gap-3 flex-1">
			<li
				class="py-4 border rounded-lg border-blue-500 text-blue-500 px-4 transition-all hover:cursor-pointer flex items-center gap-5"
			>
				<svg
					xmlns="http://www.w3.org/2000/svg"
					fill="none"
					viewBox="0 0 24 24"
					stroke-width="1.5"
					stroke="currentColor"
					class="w-6 h-6"
				>
					<path
						stroke-linecap="round"
						stroke-linejoin="round"
						d="M5.25 5.653c0-.856.917-1.398 1.667-.986l11.54 6.348a1.125 1.125 0 010 1.971l-11.54 6.347a1.125 1.125 0 01-1.667-.985V5.653z"
					/>
				</svg>

				Courses
			</li>
			<li
				class="py-4 bg-blue-500 rounded-lg text-white px-4 transition-all hover:cursor-pointer flex items-center gap-5 hover:bg-blue-400"
			>
				<svg
					xmlns="http://www.w3.org/2000/svg"
					fill="none"
					viewBox="0 0 24 24"
					stroke-width="1.5"
					stroke="currentColor"
					class="w-6 h-6"
				>
					<path
						stroke-linecap="round"
						stroke-linejoin="round"
						d="M3.75 3v11.25A2.25 2.25 0 006 16.5h2.25M3.75 3h-1.5m1.5 0h16.5m0 0h1.5m-1.5 0v11.25A2.25 2.25 0 0118 16.5h-2.25m-7.5 0h7.5m-7.5 0l-1 3m8.5-3l1 3m0 0l.5 1.5m-.5-1.5h-9.5m0 0l-.5 1.5m.75-9l3-3 2.148 2.148A12.061 12.061 0 0116.5 7.605"
					/>
				</svg>

				Past Sessions
			</li>
			<li
				class="py-4 bg-blue-500 rounded-lg text-white px-4 transition-all hover:cursor-pointer flex items-center gap-5 hover:bg-blue-400"
			>
				<svg
					xmlns="http://www.w3.org/2000/svg"
					fill="none"
					viewBox="0 0 24 24"
					stroke-width="1.5"
					stroke="currentColor"
					class="w-6 h-6"
				>
					<path
						stroke-linecap="round"
						stroke-linejoin="round"
						d="M9.594 3.94c.09-.542.56-.94 1.11-.94h2.593c.55 0 1.02.398 1.11.94l.213 1.281c.063.374.313.686.645.87.074.04.147.083.22.127.324.196.72.257 1.075.124l1.217-.456a1.125 1.125 0 011.37.49l1.296 2.247a1.125 1.125 0 01-.26 1.431l-1.003.827c-.293.24-.438.613-.431.992a6.759 6.759 0 010 .255c-.007.378.138.75.43.99l1.005.828c.424.35.534.954.26 1.43l-1.298 2.247a1.125 1.125 0 01-1.369.491l-1.217-.456c-.355-.133-.75-.072-1.076.124a6.57 6.57 0 01-.22.128c-.331.183-.581.495-.644.869l-.213 1.28c-.09.543-.56.941-1.11.941h-2.594c-.55 0-1.02-.398-1.11-.94l-.213-1.281c-.062-.374-.312-.686-.644-.87a6.52 6.52 0 01-.22-.127c-.325-.196-.72-.257-1.076-.124l-1.217.456a1.125 1.125 0 01-1.369-.49l-1.297-2.247a1.125 1.125 0 01.26-1.431l1.004-.827c.292-.24.437-.613.43-.992a6.932 6.932 0 010-.255c.007-.378-.138-.75-.43-.99l-1.004-.828a1.125 1.125 0 01-.26-1.43l1.297-2.247a1.125 1.125 0 011.37-.491l1.216.456c.356.133.751.072 1.076-.124.072-.044.146-.087.22-.128.332-.183.582-.495.644-.869l.214-1.281z"
					/>
					<path
						stroke-linecap="round"
						stroke-linejoin="round"
						d="M15 12a3 3 0 11-6 0 3 3 0 016 0z"
					/>
				</svg>

				Settings
			</li>
		</ul>

		<div class="border border-gray-400 rounded-lg flex items-center justify-between py-3 pl-2 pr-4">
			<div class="flex items-center gap-4">
				<img
					class="w-10 h-10 rounded-full bg-white"
					src="https://api.dicebear.com/7.x/adventurer/svg?seed=Angel"
					alt="user"
				/>
				<p class="font-light">Alex Johnson</p>
			</div>
			<svg
				xmlns="http://www.w3.org/2000/svg"
				fill="none"
				viewBox="0 0 24 24"
				stroke-width="1.5"
				stroke="currentColor"
				class="w-6 h-6 cursor-pointer"
			>
				<path
					stroke-linecap="round"
					stroke-linejoin="round"
					d="M15.75 9V5.25A2.25 2.25 0 0013.5 3h-6a2.25 2.25 0 00-2.25 2.25v13.5A2.25 2.25 0 007.5 21h6a2.25 2.25 0 002.25-2.25V15m3 0l3-3m0 0l-3-3m3 3H9"
				/>
			</svg>
		</div>
	</div>

	<div class="flex-1 flex flex-col">
		<div
			class="pl-10 h-28 border-b border-gray-200 bg-white flex items-center justify-between shrink-0"
		>
			<h2 class="text-lg relative">
				Course Session: <span class="font-bold">#243F9KGD</span>
				<div class="absolute -right-5 top-2 w-3 h-3 rounded-full bg-green-400 animate-pulse" />
			</h2>

			<div class="flex justify-end items-center gap-10 px-10">
				<svg
					xmlns="http://www.w3.org/2000/svg"
					fill="none"
					viewBox="0 0 24 24"
					stroke-width="1.5"
					stroke="currentColor"
					class="w-6 h-6"
				>
					<path
						stroke-linecap="round"
						d="M15.75 10.5l4.72-4.72a.75.75 0 011.28.53v11.38a.75.75 0 01-1.28.53l-4.72-4.72M4.5 18.75h9a2.25 2.25 0 002.25-2.25v-9a2.25 2.25 0 00-2.25-2.25h-9A2.25 2.25 0 002.25 7.5v9a2.25 2.25 0 002.25 2.25z"
					/>
				</svg>

				<svg
					xmlns="http://www.w3.org/2000/svg"
					fill="none"
					viewBox="0 0 24 24"
					stroke-width="1.5"
					stroke="currentColor"
					class="w-6 h-6"
				>
					<path
						stroke-linecap="round"
						stroke-linejoin="round"
						d="M3 8.25V18a2.25 2.25 0 002.25 2.25h13.5A2.25 2.25 0 0021 18V8.25m-18 0V6a2.25 2.25 0 012.25-2.25h13.5A2.25 2.25 0 0121 6v2.25m-18 0h18M5.25 6h.008v.008H5.25V6zM7.5 6h.008v.008H7.5V6zm2.25 0h.008v.008H9.75V6z"
					/>
				</svg>

				<svg
					xmlns="http://www.w3.org/2000/svg"
					fill="none"
					viewBox="0 0 24 24"
					stroke-width="1.5"
					stroke="currentColor"
					class="w-6 h-6"
				>
					<path
						stroke-linecap="round"
						stroke-linejoin="round"
						d="M7.5 8.25h9m-9 3H12m-9.75 1.51c0 1.6 1.123 2.994 2.707 3.227 1.129.166 2.27.293 3.423.379.35.026.67.21.865.501L12 21l2.755-4.133a1.14 1.14 0 01.865-.501 48.172 48.172 0 003.423-.379c1.584-.233 2.707-1.626 2.707-3.228V6.741c0-1.602-1.123-2.995-2.707-3.228A48.394 48.394 0 0012 3c-2.392 0-4.744.175-7.043.513C3.373 3.746 2.25 5.14 2.25 6.741v6.018z"
					/>
				</svg>

				<svg
					xmlns="http://www.w3.org/2000/svg"
					fill="none"
					viewBox="0 0 24 24"
					stroke-width="1.5"
					stroke="currentColor"
					class="w-6 h-6"
				>
					<path
						stroke-linecap="round"
						stroke-linejoin="round"
						d="M14.857 17.082a23.848 23.848 0 005.454-1.31A8.967 8.967 0 0118 9.75v-.7V9A6 6 0 006 9v.75a8.967 8.967 0 01-2.312 6.022c1.733.64 3.56 1.085 5.455 1.31m5.714 0a24.255 24.255 0 01-5.714 0m5.714 0a3 3 0 11-5.714 0"
					/>
				</svg>
				<svg
					xmlns="http://www.w3.org/2000/svg"
					fill="none"
					viewBox="0 0 24 24"
					stroke-width="1.5"
					stroke="currentColor"
					class="w-6 h-6"
				>
					<path
						stroke-linecap="round"
						stroke-linejoin="round"
						d="M2.25 12l8.954-8.955c.44-.439 1.152-.439 1.591 0L21.75 12M4.5 9.75v10.125c0 .621.504 1.125 1.125 1.125H9.75v-4.875c0-.621.504-1.125 1.125-1.125h2.25c.621 0 1.125.504 1.125 1.125V21h4.125c.621 0 1.125-.504 1.125-1.125V9.75M8.25 21h8.25"
					/>
				</svg>
			</div>
		</div>

		<div class="flex-1 bg-gray-100 flex">
			<div class="flex-1 p-10 flex">
				<div class="bg-white p-10 flex rounded-lg">
					<div class="w-[60%] shrink-0">
						<div class="h-[300px] rounded-lg border bg-gray-100 flex items-center justify-center">
							<Loader />
						</div>
						<h2 class="text-2xl border-b pb-3 mt-5">
							Title: <span class="font-medium">Code with a cup of <s>coffee</s></span>
						</h2>
						<p class="text-sm mt-2">
							Something that sucks not always the same the thing that sucks, sometimes we need to
							look back and see what we left, well am I really talking about coding nah?? Oops I
							miss the track well no problem its fine let's move to coding and stop thinking about
							everything but ofcourse don't remember the one who created you, fullfill his duties
							and let's do coding
						</p>
					</div>
					<div class="flex flex-col gap-4">
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
							<p class="text-5xl text-blue-500">00:49:59s</p>
						</div>
					</div>
				</div>
			</div>

			<div class="p-5 w-1/4 flex flex-col h-full bg-white border-l border-gray-200">
				<h1 class="text-lg font-medium border-b border-gray-200 pb-3">Students</h1>
				<div class="h-full mt-5 flex flex-col gap-3">
					{#each Array(10).fill(0) as _}
						<div
							class="w-full border border-gray-200 rounded-lg py-2 px-2 flex items-center gap-5 transition-all hover:border-gray-400 cursor-pointer relative"
						>
							<img
								src="https://api.dicebear.com/7.x/avataaars/svg?seed=Bella"
								alt="user"
								class="w-10 h-10 rounded-full"
							/>
							<p class="font-light">Akmal Hossain Raj</p>
							<div class="absolute right-4 w-3 h-3 rounded-full bg-green-400 animate-pulse" />
						</div>
					{/each}
				</div>
			</div>
		</div>
	</div>
</div>
