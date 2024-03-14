<script>
	import Footer from '$lib/footer.svelte';
	import Header from '$lib/header.svelte';

	import { dev } from '$app/environment';
	import { inject } from '@vercel/analytics'

	inject({ mode: dev ? 'development' : 'production' });
	
</script>

<Header />
<slot />
<Footer />
