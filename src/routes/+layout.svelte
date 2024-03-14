<script>
	import Footer from '$lib/footer.svelte';
	import Header from '$lib/header.svelte';

	import { dev } from '$app/environment';
	import { inject } from '@vercel/analytics'
	import { injectSpeedInsights } from '@vercel/speed-insights/sveltekit';

	inject({ mode: dev ? 'development' : 'production' });
	injectSpeedInsights();
</script>

<Header />
<slot />
<Footer />
