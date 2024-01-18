<script>
	import logo from '$lib/assets/instagram.png';

	const firstYear = 2024;
	var date = new Date();
</script>

<div>
	{#if date.getFullYear() > firstYear}
		<p>Copyright © {firstYear} - {date.getFullYear()} Automata BCN</p>
	{:else}
		<p>Copyright © 2024 Automata BCN</p>
	{/if}
</div>

<style>
	p {
		text-align: center;
	}
</style>
