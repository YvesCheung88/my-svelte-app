<div class="section">
	<div class="boxed">
		<div class="flex toColumn mCenter">
			<div class="w40 wm100">
				<h2>A Propos de moi</h2>
			</div>
			<div class="w60 wm100">
				<p>
					Lorem ipsum dolor sit amet, consectetur adipisicing elit. Deserunt, aperiam nam? Deleniti
					iure corrupti rerum cupiditate soluta exercitationem pariatur, voluptatum laudantium aut,
					commodi quam nobis nesciunt vero minima fugit suscipit!
				</p>
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
	.flex {
		display: flex;
	}
	h2 {
		font-size: 3rem;
		margin-bottom: 100px;
	}
	.w40 {
		width: 40%;
	}
	.w60 {
		width: 60%;
	}
	@media (max-width: 810px) {
		.section {
			padding: 50px 0;
		}
		.boxed {
			max-width: 90%;
		}
		h2 {
			font-size: 1.75rem;
			margin-bottom: 30px;
		}
		.toColumn {
			flex-direction: column;
		}
		.mCenter {
			justify-content: center;
			align-items: center;
			text-align: center;
		}
		.wm100 {
			width: 100%;
		}
	}
</style>
