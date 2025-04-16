<script>

	import Detalle from "$lib/components/Detalle.svelte";
</script>




  
  <section>
    <div class="cabecera">
      <div class="cabecera__video">
      </div>
      <div class="cabecera__detalle">
   <Detalle></Detalle>

      </div>
    </div>

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
    }
  </style>
