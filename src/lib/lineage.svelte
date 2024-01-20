<script>
	import WSL from '$lib/assets/wong_sun_leung.png';
	import Dido from '$lib/assets/dido_pb.png';
</script>

<div id="lineage">
	<article>
		<header>
			<h3>Linaje</h3>
		</header>
		<div id="body">
			<details id="wsl" open>
				<summary><strong>Wong Shun Leung</strong></summary>
				<div>
					<div>
						<img class="center" alt="wong_shun_leung" src={WSL} width="500" />
					</div>
					<div>
						<p>
							<strong>Wong Shun Leung</strong> fue el luchador más famoso del sistema Ving Tsun. Fue
							el principal responsable del entrenamiento en artes marciales de Bruce Lee.
						</p>
					</div>
				</div>
			</details>
			<details id="pb" open>
				<summary><strong>Phillip Bayer</strong></summary>
				<div>
					<div>
						<img
							class="center"
							alt="philipp_bayer_wong_shun_leung"
							src="https://vingtsun.info/images/WongShunLeung_PhilippBayer.jpg"
						/>
					</div>
					<div>
						<p>
							En 1983, <strong>Philipp Bayer</strong> comenzó su formación con Wong Shun Leung en Hong
							Kong y en 1990 fundó la Asociación Europea de Kung Fu Ving Tsun.
						</p>
						<div class="link" style="text-align:center">
							<a target="_blank" href="https://vingtsun.info/">
								Ving Tsun Kung Fu - Philipp Bayer
							</a>
						</div>
						<div class="link" style="text-align:center">
							<a
								target="_blank"
								href="https://www.facebook.com/100066487362775/posts/710213171204922/"
								>Entrevista sobre Ving Tsun</a
							>
						</div>
						<div class="link" style="text-align:center">
							<a target="_blank" href="https://www.youtube.com/watch?v=JZPNutCbg9Q"
								>Video: Ejemplo de su estilo</a
							>
						</div>
					</div>
				</div>
			</details>
			<details id="dido" open>
				<summary><strong>Dido</strong></summary>
				<div>
					<div>
						<img class="center" alt="dido_philipp_bayer" src={Dido} />
					</div>
					<div>
						<p>
							Con 10 años siguiendo el linaje de Philipp Bayer, Dido enseña Ving Tsun en Barcelona
							desde 2022.
						</p>
						<div style="text-align:center">
							Síguenos en <a target="_blank" href="https://www.instagram.com/automatabcn/"
								>Instagram</a
							>
						</div>
					</div>
				</div>
			</details>
		</div>
	</article>
</div>

<style>
	h3 {
		margin-bottom: 0px;
	}
	img {
		width: 300px;
	}
	.link {
		margin: 1rem;
	}
	.center {
		display: block;
		margin-left: auto;
		margin-right: auto;
		margin-top: 1rem;
		margin-bottom: 1rem;
	}
</style>
