<div class="detallepopup">
	<div class="calorias">
		<p class="numero">416</p>
		<p class="unidades">kcal/ración</p>
	</div>
	<div class="barritas">
		<div class="infobarritas grasas">
			<p class="nome">Grasas</p>
			<p class="kcal">227Kcal</p>
			<p class="peso">25gr</p>
			<div class="progreso"><progress class="prgrasas" max="100" value="54"></progress></div>
			<p class="porcentaxe">54%</p>
		</div>
		<div class="infobarritas hidratos">
			<p class="nome">Hidratos</p>
			<p class="kcal">166Kcal</p>
			<p class="peso">42gr</p>
			<div class="progreso"><progress class="prhidratos" max="100" value="39"></progress></div>
			<p class="porcentaxe">39%</p>
		</div>

		<div class="infobarritas proteinas">
			<p class="nome">Proteínas</p>
			<p class="kcal">23Kcal</p>
			<p class="peso">6gr</p>
			<div class="progreso"><progress class="prproteinas" max="100" value="7"></progress></div>
			<p class="porcentaxe">7%</p>
		</div>
	</div>
</div>

<style>
	.detallepopup {
		display: flex;
		width: 100%;
	}
	.calorias {
		display: flex;
		flex-direction: column;
		width: 20%;
	}
	.numero {
		color: #000;

		font-size: 36px;
		font-style: normal;
		font-weight: 700;
		line-height: normal;
	}
	.unidades {
		color: #000;

		font-size: 13px;
		font-style: normal;
		font-weight: 400;
		line-height: normal;
	}
	.calorias p {
		text-align: center;
	}
	.barritas {
		display: flex;
		flex-direction: column;
		width: 80%;
	}
	.infobarritas {
		display: flex;
		align-items: center;
		justify-content: space-between;
	}
	.nome {
		width: 20%;
	}
	.kcal {
		width: 20%;
	}
	.peso {
		width: 5%;
	}
	.porcentaxe {
		width: 5%;
	}
	.progreso {
		width: 50%;
       
	}
	.progreso progress {
		width: 90%;
	}
	.prgrasas {
		box-shadow: rgb(207, 207, 125);
	}
	.grasas {
		color: rgb(207, 207, 125);
	}
	.hidratos {
		color: red;
	}
	.proteinas {
		color: green;
	}
</style>
