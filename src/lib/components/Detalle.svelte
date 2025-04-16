<section class="detalle">
	<div class="detalle__description">
		<img src="Detalle/dificultad.svg" alt="" />
		<p>Media</p>
	</div>
	<div class="detalle__description">
		<img src="Detalle/personas.png" alt="" />
		<p>10-12 personas</p>
	</div>
	<div class="detalle__description">
		<img src="/Detalle/tiempo.png" alt="" />
		<p>30 min. de preparación</p>
	</div>
	<div class="detalle__description">
		<img src="/Detalle/coccion.png" alt="" />
		<p>50 min. de cocción</p>
	</div>
</section>

<style>
    @font-face {
    font-family: Nunito;
    src: url('src/routes/Styles/Fonts/Nunito-VariableFont_wght.ttf');
    }
    .detalle{
        display: flex;
        flex-wrap: wrap;
        font-family: Nunito;
        font-weight: 400;
        font-size: 16px;
        background-color: #F7F7F7;
    }
    .detalle__description{
        display: flex;
        gap: 10px;
        align-items: center;
        flex: 0 0 50%;
        box-sizing: border-box;
    }
    .detalle__description img{
        width: 34px;
        height: 34px;
    }
    .detalle__description p{
        white-space: nowrap;
    }
</style>
