<script>
	import '../app.css';

	import Header from '$lib/components/Header.svelte';

	export let data;
</script>

<div class="text-slate-800">
  <h1>PRELTEKIT STARTER</h1>
	<Header navigation={data.navigation} settings={data.settings} />
	<main><slot /></main>
</div>
