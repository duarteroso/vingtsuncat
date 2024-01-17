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
	div {
		align-content: center;
	}
	p {
		text-align: center;
		vertical-align: middle;
	}
	footer {
		bottom: 0;
		width: 100%;
		height: 2rem;
		position: fixed;
		background: #11191fdb;
		color: #fff;
	}
</style>
