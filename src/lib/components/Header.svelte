<script>
</script>

<header class="header">
	<img class="header__img" src="nestle-cocina-logo.png" alt="logo Nestle" />
	<nav class="nav">
		<a class="nav__a" href="#recetas">RECETAS</a>
		<a class="nav__a" href="#cocinaCon">COCINA CON</a>
		<a class="nav__a" href="#consejos">CONSEJOS</a>
		<a class="nav__a" href="#cupones">CUPONES</a>
		<a class="nav__a" href="#menuPlanner">MENÚ PLANNER</a>
		<a class="nav__a" href="#alimentacionSostenible">ALIMENTACIÓN SOSTENIBLE</a>
		<a class="nav__a nav__border" href="#cocinaReels">COCINA REELS</a>
	</nav>
</header>

<style>
	.header {
		background: #f7f7f7;
		width: 100vw;
		height: 84px;
		display: flex;
		align-items: center;
	}

	.header__img {
		width: 151px;
		margin-left: 18px;
		margin-right: 71px;
	}

	.nav {
		display: flex;
		justify-content: flex-start;
		flex-wrap: wrap;
		gap: 7px;
		width: 100%;
	}

	.nav__a {
		color: #565458;
		font-size: 14px;
		font-weight: 700;
		text-decoration: none;
		text-align: center;
		border-right: 2px solid #565458;
		padding: 0 1%;
		transition: all 0.5s ease;
		&:hover {
			background: #5654582c;
			transform: scale(1.1);
		}
	}

	.nav__border {
		border: none;
	}
</style>
