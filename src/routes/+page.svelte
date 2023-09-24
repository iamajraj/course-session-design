<script>
	import Content from '../components/Content.svelte';
	import Navbar from '../components/Navbar.svelte';
	import Sidebar from '../components/Sidebar.svelte';
	import StudentsList from '../components/StudentsList.svelte';
</script>

<div class="w-full h-full flex">
	<Sidebar />
	<div class="flex-1 flex flex-col">
		<Navbar />
		<div class="flex-1 bg-gray-100 flex">
			<Content />
			<StudentsList />
		</div>
	</div>
</div>
