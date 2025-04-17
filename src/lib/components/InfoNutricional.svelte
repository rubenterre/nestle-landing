<div class="down">
	<div class="titular">
		<h3>Información nutricional adicional por ración:</h3>
		<div class="principal">
			<div id="left" class="left">
				<div class="info__l">
					<div class="azucar__racion">
						<div id="left__azucar" class="azucar">Azúcar</div>
						<div id="left__grs" class="grs__azucar">33,00 gr.</div>
					</div>
					<div class="ldl__racion">
						<div id="left__ldl" class="ldl">Grasas saturadas</div>
						<div id="left__gr" class="grs__ldl">12,40 gr.</div>
					</div>
				</div>
			</div>
			<div id="right" class="right">
				<div class="info__down">
					<div class="right__azucar">
						<div id="right__azucar" class="azucar">Azúcar</div>
						<div id="right__grs" class="grs__azucar">2.30 gr.</div>
					</div>
					<div class="right__ldl">
						<div id="right__ldl" class="ldl">Grasas saturadas</div>
						<div id="right__gr" class="grs__ldl">1,24 gr.</div>
					</div>
				</div>
			</div>
		</div>
	</div>
</div>

<style>	
.principal {
    display: flex;
}

	.azucar {
		height: 1.12rem;
		width: 6.31rem;
	}
	.ldl {
		height: 1.12rem;
		width: 6.31rem;
	}

	.down {
		width: 80vw;
		height: 110px;
		font-size: 0.81rem;
		font-family: Nunito;
		background-color: white;
	}
	h3 {
		font-weight: 400;
		font-size: 0.81rem;
	}
	.titular {
		width: 15.8rem;
		height: 1.12rem;
		margin-top: 0.8rem;
		margin-left: 1.18rem;
	}

	.right__azucar {
		display: flex;
	}

	.right {
		display: flex;
		flex-direction: column;
		margin-left: 14rem;
	}

	.info__l {
		display: flex;
		flex-direction: column;
	}
	.azucar__racion {
		display: flex;
	}
	.ldl__racion {
		display: flex;
	}
	.info__down {
		display: flex;
		flex-direction: column;
	}
	.right__ldl {
		display: flex;
	}
	.grs__azucar {
        height: 1.12rem;
		width: 3.37rem;
		font-weight: bold;
        margin-left: 1rem;
	}
	.grs__ldl {
		font-weight: bold;
         margin-left: 1rem;
	}
   
    
</style>
