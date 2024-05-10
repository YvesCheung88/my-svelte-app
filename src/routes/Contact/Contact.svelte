<div class="section dark">
	<div class="boxed text-center">
		<h2>Contactez-moi</h2>
		<div class="flex toColumn space-between mgap20">
			<div class="w32 wm100 contact">
				<span class="material-icons icon">mail </span>
				<span class="label">E-mail </span>
				<span class="value">test </span>
			</div>
			<div class="w32 wm100 contact">
				<span class="material-icons icon">mail </span>
				<span class="label">E-mail </span>
				<span class="value">test </span>
			</div>
			<div class="w32 wm100 contact">
				<span class="material-icons icon">mail </span>
				<span class="label">E-mail </span>
				<span class="value">test </span>
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
	.space-between {
		justify-content: space-between;
	}
	.w32 {
		width: 32%;
	}
	.icon {
		display: block;
		font-size: 40px;
	}
	.label {
		display: block;
		font-weight: 700;
		text-transform: uppercase;
		margin: 10px 0;
		font-size: 1.5rem;
	}
	.value {
		display: block;
		font-size: 1.5rem;
	}
	.contact {
		border: 2px dashed #fff;
		border-radius: 15px;
		padding: 30px;
		box-sizing: border-box;
	}
	@media (max-width: 810px) {
		.toColumn {
			flex-direction: column;
		}
		.mgap20 {
			gap: 20px;
		}
		.wm100 {
			width: 100%;
		}
	}
</style>
