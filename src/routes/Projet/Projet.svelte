<div class="section">
	<div class="boxed text-center">
		<h2>Mes projets</h2>
		<div class="flex wrap gap20 space-between">
			<div class="w32 wm47 realisation">
				<a href="/">
					<img src="chateau-de-lesigny.jpeg" alt="" />
					<h3>Site de mon projet</h3>
				</a>
			</div>
			<div class="w32 wm47 realisation">
				<a href="/">
					<img src="chateau-de-lesigny.jpeg" alt="" />
				</a>
			</div>
			<div class="w32 wm47 realisation">
				<a href="/">
					<img src="chateau-de-lesigny.jpeg" alt="" />
				</a>
			</div>
			<div class="w32 wm47 realisation">
				<a href="/">
					<img src="chateau-de-lesigny.jpeg" alt="" />
				</a>
			</div>
			<div class="w32 wm47 realisation">
				<a href="/">
					<img src="chateau-de-lesigny.jpeg" alt="" />
				</a>
			</div>
			<div class="w32 wm47 realisation">
				<a href="/">
					<img src="chateau-de-lesigny.jpeg" alt="" />
				</a>
			</div>
		</div>
	</div>
</div>

<style>
	.section {
		padding: 100px 0;
	}
	.boxed {
		max-width: 1280px;
		margin-inline: auto;
	}
	.text-center {
		text-align: center;
	}
	h2 {
		font-size: 3rem;
		margin-bottom: 100px;
	}
	.flex {
		display: flex;
	}
	.wrap {
		flex-wrap: wrap;
	}
	.gap20 {
		gap: 20px;
	}
	.space-between {
		justify-content: space-between;
	}
	.w32 {
		width: 32%;
	}
	.realisation {
		height: auto;
		aspect-ratio: 1/1;
		position: relative;
	}
	.realisation h3 {
		position: absolute;
		top: 50%;
		left: 50%;
		transform: translate(-50%, -50%);
		font-size: 2rem;
		width: max-content;
	}
	.realisation a {
		display: block;
		width: 100%;
		height: 100%;
		text-decoration: none;
		color: #fff;
	}
	.realisation img {
		width: 100%;
		height: 100%;
		object-fit: cover;
		filter: brightness(40%);
		transition: 0.4s ease;
	}
	.realisation:hover img {
		filter: brightness(60%);
	}
	@media (max-width: 810px) {
		.wm47 {
			width: 47%;
		}
	}
</style>
