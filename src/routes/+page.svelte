<script>
	import Description from "$lib/components/Description.svelte";
	import Titulo from "$lib/components/Titulo.svelte";
	import Detalle from "$lib/components/Detalle.svelte";
	import AporteNutricional from "$lib/components/AporteNutricional.svelte";
</script>

  <section>
    <div class="cabecera">
      <div class="cabecera__video">
      </div>
      <div class="cabecera__detalle">
        <Titulo></Titulo>
        <Detalle></Detalle>
        <AporteNutricional></AporteNutricional>
      </div>
    </div>
<Description></Description>

  </section>
  
  <style>
    .cabecera {
      display: grid;
      grid-template-columns: 1fr 1fr;
      background-color: var(--cor-principal);
      margin-top: 30px;
    }
  
    .cabecera__video {
      position: relative;
      width: 100%;
      padding-bottom: 56.25%;
    }
  
    .cabecera__detalle {
      padding: 50px;
      display: flex;
      justify-content: space-between;
      flex-direction: column;
      gap: 30px;
    }
  </style>