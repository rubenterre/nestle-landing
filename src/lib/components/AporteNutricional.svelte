<script>

</script>

<div class="aporte-nutricional-contenedor">
	<div class="texto-info">
		<span class="titulo">Qué me aporta esta receta...</span>
		<span class="subtitulo">Información nutricional</span>
	</div>
	<div class="icono">+</div>
</div>

<style>
	.aporte-nutricional-contenedor {
		display: flex;
		justify-content: space-between;
		align-items: center;
		background-color: #e0f2fe;
		padding: 1rem;
	}

	.texto-info {
		display: flex;
		flex-direction: column;
	}

	.titulo {
		font-weight: bold;
		font-size: 1em;
		color: #333;
		margin-bottom: 0.25rem;
	}

	.subtitulo {
		font-size: 0.9em;
		color: #555;
        border-radius: 4px;
		cursor: pointer;
		margin-bottom: 1rem;
		border: 1px solid #bce0f7;
	}

	.icono {
		font-size: 1.5em;
		font-weight: bold;
		color: #333;
		padding: 0 0.5rem;
	}

	.aporte-nutricional-contenedor:hover {
		background-color: #ccebfd;
	}
</style>
