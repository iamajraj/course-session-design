<script lang="ts">
	let remainingHour = 0;
	let remainingMin = 49;
	let remainingSec = 59;
	let id: number;

	let hour: string = '00';
	let min: string = '00';
	let sec: string = '00';

	id = setInterval(() => {
		min = remainingMin < 10 ? '0' + remainingMin : String(remainingMin);
		hour = remainingHour < 10 ? '0' + remainingHour : String(remainingHour);
		sec = remainingSec < 10 ? '0' + remainingSec : String(remainingSec);

		if (remainingHour === 0 && remainingMin === 0 && remainingSec === 0) {
			return clearInterval(id);
		}
		if (remainingSec === 0) {
			remainingMin = remainingMin > 0 ? (remainingMin -= 1) : 0;
			remainingSec = remainingMin > 0 ? 60 : 0;
		}
		if (remainingMin === 0) {
			remainingHour = remainingHour > 0 ? (remainingHour -= 1) : 0;
			remainingMin = remainingHour > 0 ? 60 : 0;
		}
		remainingSec--;
	}, 1000);
</script>

<p class="text-5xl text-blue-500 mb-5">{hour}:{min}:{sec}s</p>
