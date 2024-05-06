<script>
</script>

<div class="slider">
	<img
		src="backgd-img.webp"
		class="slider-background"
		alt="developpeur web avec un casque devant un ordinateur"
	/>
	<div class="slider-content">
		<h1>Cheung Yves</h1>
		<p>Je suis developpeur web junior</p>
	</div>
</div>
<div class="section">
	<div class="boxed">
		<div class="flex">
			<div class="w40">
				<h2>A Propos de moi</h2>
			</div>
			<div class="w60">
				<p>
					Lorem ipsum dolor sit amet, consectetur adipisicing elit. Deserunt, aperiam nam? Deleniti
					iure corrupti rerum cupiditate soluta exercitationem pariatur, voluptatum laudantium aut,
					commodi quam nobis nesciunt vero minima fugit suscipit!
				</p>
			</div>
		</div>
	</div>
</div>
<div class="section dark">
	<div class="boxed text-center">
		<h2>Découvrez mes compétences</h2>
		<div class="flex gap20">
			<div class="w25 skill">
				<img src="html.png" alt="HTML logo" />
				<h3>HTML</h3>
			</div>
			<div class="w25 skill">
				<img src="css.png" alt="HTML logo" />
				<h3>CSS</h3>
			</div>
			<div class="w25 skill">
				<img src="typescript.png" alt="HTML logo" />
				<h3>Typescript</h3>
			</div>
			<div class="w25 skill">
				<img src="svelte.png" alt="HTML logo" />
				<h3>Svelte</h3>
			</div>
		</div>
	</div>
</div>
<div class="section">
	<div class="boxed text-center">
		<h2>Mes projets</h2>
		<div class="flex space-bewteen">
			<div class="w32 realisation">
				<a href="/">
					<img src="chateau-de-lesigny.jpeg" alt="" />
					<h3>Site de mon projet</h3>
				</a>
			</div>
			<div class="w32 realisation">
				<a href="/">
					<img src="chateau-de-lesigny.jpeg" alt="" />
				</a>
			</div>
			<div class="w32 realisation">
				<a href="/">
					<img src="chateau-de-lesigny.jpeg" alt="" />
				</a>
			</div>
		</div>
	</div>
</div>

<style>
	@import url('https://fonts.googleapis.com/css2?family=Roboto:ital,wght@0,100;0,300;0,400;0,500;0,700;0,900;1,100;1,300;1,400;1,500;1,700;1,900&display=swap');

	:global(body) {
		font-family: 'Roboto', sans-serif;
		margin: 0;
		padding: 0;
	}
	.slider {
		width: 100%;
		min-height: 80vh;
		aspect-ratio: 16/9;
		background-color: #000;
	}
	.slider-background {
		width: 100%;
		height: 100%;
		object-fit: cover;
		filter: brightness(50%);
	}
	.slider-content {
		position: absolute;
		top: 50%;
		left: 50%;
		transform: translate(-50%, -50%);
		text-align: center;
	}
	h1 {
		color: #fff;
		font-size: 5rem;
	}
	h2 {
		font-size: 3rem;
		margin-bottom: 100px;
	}
	p {
		font-size: 1.5rem;
		line-height: 1.5em;
	}
	.slider-content p {
		color: #fff;
		font-size: 2rem;
		font-weight: 300;
	}
	.section {
		padding: 100px 0;
	}
	.boxed {
		max-width: 1280px;
		margin-inline: auto;
	}
	.flex {
		display: flex;
	}
	.dark {
		background: #000;
		color: #fff;
	}
	.w40 {
		width: 40%;
	}
	.w60 {
		width: 60%;
	}
	.text-center {
		text-align: center;
	}
	.w25 {
		width: 25%;
	}
	.w32 {
		width: 32%;
	}
	.space-bewteen {
		justify-content: space-between;
	}
	.gap20 {
		gap: 20px;
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
</style>
