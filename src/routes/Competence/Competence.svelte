<div class="section dark">
	<div class="boxed text-center">
		<h2>Découvrez mes compétences</h2>
		<div class="flex toColumn gap20">
			<div class="w25 wm100 skill">
				<img src="html.png" alt="HTML logo" />
				<h3>HTML</h3>
			</div>
			<div class="w25 wm100 skill">
				<img src="css.png" alt="HTML logo" />
				<h3>CSS</h3>
			</div>
			<div class="w25 wm100 skill">
				<img src="typescript.png" alt="HTML logo" />
				<h3>Typescript</h3>
			</div>
			<div class="w25 wm100 skill">
				<img src="svelte.png" alt="HTML logo" />
				<h3>Svelte</h3>
			</div>
		</div>
	</div>
</div>

<style>
	.section {
		padding: 100px 0;
	}
	.dark {
		background: linear-gradient(rgba(0, 0, 0, 0.6), rgba(0, 0, 0, 0.6)), url(/backgd-img.webp);
		background-size: cover;
		background-position-y: 50%;
		color: #fff;
	}
	.boxed {
		max-width: 1280px;
		margin-inline: auto;
	}
	.text-center {
		text-align: center;
	}
	.flex {
		display: flex;
	}
	.gap20 {
		gap: 20px;
	}
	.w25 {
		width: 25%;
	}
	.skill {
		background: #fff;
		border-radius: 15px;
		padding: 20px;
		box-sizing: border-box;
	}
	.skill img {
		width: 100px;
		aspect-ratio: 1/1;
		object-fit: contain;
	}
	.skill h3 {
		margin-top: 10px;
		color: #000;
	}
	@media (max-width: 810px) {
		.toColumn {
			flex-direction: column;
		}
		.wm100 {
			width: 100%;
		}
	}
</style>
