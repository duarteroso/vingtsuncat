<script>
	import Info from '$lib/info.svelte';
	import Contact from '$lib/contact.svelte';
	import Lineage from '$lib/lineage.svelte';
	import Vingtsun from '$lib/vingtsun.svelte';
	import Automata from '$lib/assets/automata.png';
	import Footer from '$lib/footer.svelte';
</script>

<div class="content">
	<div id="top">
		<p>Introduction</p>
	</div>
	<Vingtsun />
	<Lineage />
	<Info />
	<Contact />
</div>

<style>
	.content {
		padding-top: 3rem;
		padding-bottom: 40px;
	}
</style>
