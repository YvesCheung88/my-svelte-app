<script lang="ts">
	let isOpen = false;

	function toggleMenu() {
		isOpen = !isOpen;
	}
</script>

<header>
	<div class="boxed">
		<div class="flex aligncenter space-between">
			<button class="menu-button" aria-label="Toggle Menu" on:click={toggleMenu}>
				<span class="material-icons">{isOpen ? 'close' : 'menu'}</span>
			</button>

			<a href="/" class="header-logo">
				<img src="html.png" alt="" />
			</a>
			<ul class="header-menu">
				<li><a href="/">Accueil</a></li>
				<li><a href="/">A propos</a></li>
				<li><a href="/">Projet</a></li>
				<li><a href="/">Contact</a></li>
			</ul>
		</div>
	</div>
</header>

<style>
	header {
		position: fixed;
		top: 0;
		left: 0;
		width: 100%;
		background: #fff;
		z-index: 999;
		padding-block: 10px;
		box-shadow: 1px 1px 25px rgba(0, 0, 0, 0.7);
	}

	.header-logo {
		display: block;
	}
	.header-logo img {
		width: 60px;
	}
	.header-menu {
		display: flex;
		align-items: center;
		list-style: none;
	}
	.header-menu li a {
		text-decoration: none;
		color: #000;
		padding: 10px 20px;
		display: block;
		box-sizing: border-box;
	}
	.header-menu li a:hover {
		background-color: #f2f2f2;
	}
	.header-menu li:last-child a {
		background-color: #f06423;
		color: #fff;
	}
	.boxed {
		max-width: 1280px;
		margin-inline: auto;
	}
	.flex {
		display: flex;
	}
	.aligncenter {
		align-items: center;
	}
	.space-between {
		justify-content: space-between;
	}

	@media (max-width: 810px) {
		header {
			height: 60px;
		}
		button {
			display: block;
			border: 0px;
			background-color: #fff;
			position: absolute;
			left: 5%;
			top: 50%;
			transform: translateY(-50%);
		}
		.header-logo {
			position: absolute;
			top: 50%;
			left: 50%;
			transform: translate(-50%, -50%);
		}
		.header-menu {
			position: fixed;
			top: 0;
			left: 0;
			width: 100%;
			height: 100vh;
			background-color: #fff;
			flex-direction: column;
			align-items: center;
			justify-content: center;
			gap: 30px;
			display: none;
		}
		.header-menu li:last-child a {
			margin-top: 10px;
		}
	}
</style>
