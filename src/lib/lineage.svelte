<script>
	import WSL from '$lib/assets/wong_sun_leung.png';
	import Dido from '$lib/assets/dido_pb.png';
	import Instagram from '$lib/assets/instagram.png';
	import WWW from '$lib/assets/www.png';
</script>

<h3>Linia</h3>
<div id="lineage">
	<article>
		<header><h5>Wong Shun Leung</h5></header>
		<div>
			<div>
				<img class="center" alt="wong_shun_leung" src={WSL} width="500" />
			</div>
			<div>
				<p>
					<strong>Wong Shun Leung</strong> fue el luchador más famoso del sistema Ving Tsun y también
					fue el principal responsable del entrenamiento en artes marciales de Bruce Lee.
				</p>
			</div>
		</div>
	</article>

	<article>
		<header><h5>Phillip Bayer</h5></header>
		<div class="grid">
			<div>
				<img
					class="center"
					alt="philipp_bayer_wong_shun_leung"
					src="https://vingtsun.info/images/WongShunLeung_PhilippBayer.jpg"
				/>
			</div>
			<div>
				<p>
					En 1983, <strong>Philipp Bayer</strong> comenzó su formación con Wong Shun Leung en Hong Kong
					y en 1990 fundó la Asociación Europea de Kung Fu Ving Tsun.
				</p>
				<div style="text-align:center">
					<a target="_blank" href="https://vingtsun.info/">
						<img src={WWW} alt="website" width="50" height="50" />
					</a>
				</div>
			</div>
		</div>
	</article>

	<article>
		<header><h5>Dido</h5></header>
		<div class="grid">
			<div>
				<img class="center" alt="dido_philipp_bayer" src={Dido} />
			</div>
			<div>
				<p>?</p>
				<div style="text-align:center">
					<a target="_blank" href="https://www.instagram.com/automatabcn/">
						<img src={Instagram} alt="instagram" width="50" height="50" />
					</a>
				</div>
			</div>
		</div>
	</article>
</div>

<style>
	h5 {
		margin: 0px;
	}
	.center {
		display: block;
		margin-left: auto;
		margin-right: auto;
		margin-top: 1rem;
		margin-bottom: 1rem;
	}
</style>
