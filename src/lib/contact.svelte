<script>
	import facebook from '$lib/assets/facebook.png';
	import instagram from '$lib/assets/instagram.png';
</script>

<h3>Contato</h3>
<article id="contact">
	<ul>
		<li>
			<a target="_blank" href="https://www.instagram.com/automatabcn/">
				<img src={instagram} alt="instagram" width="64" height="64" />
			</a>
		</li>
		<li>
			<a target="_blank" href="">
				<img src={facebook} alt="instagram" width="64" height="64" />
			</a>
		</li>
	</ul>
</article>

<style>
	ul {
		display: block;
		justify-content: center;
		justify-items: center;
	}
	li {
		list-style-type: none;
	}
</style>
