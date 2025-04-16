<script>

export let visible = false;

function closePopup() {
  visible = false;
}
</script>

{#if visible}
  <div class="popup">
    <div class="popup-contenido">
      <p>Esta receta me aporta...</p>
      <div class="popup__datos">
      
      </div>
      <div class="popup__info">
        
      </div>
      <div class="popup__cerrar">
        <button on:click={closePopup}>Cerrar</button>
      </div>
    </div>
  </div>
{/if}

<style>
  /* Estilos para Popup.svelte */
  .popup {
    position: fixed;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background: rgba(0, 0, 0, 0.7);
    display: flex;
    align-items: center;
    justify-content: center;
  }

  .popup-contenido {
    background: var(--cor-principal);
    border-radius: 5px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.3);
    padding: 40px;
  }

  .popup__cerrar {
    display: flex;
    justify-content: center;
    align-content: center;
  }

  p {
    color: black;
    font-family: var(--fonte-principal);
    font-size: 1.3rem;
    font-style: normal;
    font-weight: 500;
    line-height: normal;
    margin-bottom: 30px;
  }

  button {
    width: 281px;
    height: 49px;
    font-size: 1.3rem;
    color: #555;
    cursor: pointer;
    border: 1px solid #979797;
    background: #fff;
  }
</style>
