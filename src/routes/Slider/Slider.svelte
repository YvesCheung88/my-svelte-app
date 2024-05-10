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

<style>
	.slider {
		width: 100%;
		min-height: 80vh;
		aspect-ratio: 16/9;
		background-color: #000;
		position: relative;
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
	p {
		font-size: 1.5rem;
		line-height: 1.5em;
	}
	.slider-content p {
		color: #fff;
		font-size: 2rem;
		font-weight: 300;
	}
	@media (max-width: 810px) {
		.slider {
			height: 60vh;
		}
		.slider-content {
			width: 90%;
		}
		.slider-content p {
			margin-top: 20px;
			font-size: 1.5rem;
		}
		h1 {
			font-size: 2rem;
		}
		p {
			font-size: 1rem;
			text-wrap: balance;
		}
	}
</style>
