<script>
	import Footer from "$lib/components/Footer.svelte";
	import Header from '$lib/components/Header.svelte';
</script>

<Header></Header>

  
  <slot/>
  
  <Footer></Footer>
  <style>
  
  @font-face{
      font-family: Nunito;
      src: url(styles/fonts/Nunito-VariableFont_wght.ttf);
  }
  
  :root{
      --cor-principal: #F7F7F7;
      --cor-secundario: #343239;
      --fonte-principal: Nunito;
  }
  
  :global(*){
    margin: 0;
    padding: 0;
    outline: 0;
    box-sizing: border-box;
  }
  
  :global(body){
      background: white;
      font-size: 16px;
      color: var(--cor-secundario)
  }
  
  :global(body, input, button) {
   font-size: 14px;
   font-family: var(--fonte-principal);
  }
  
  :global(button) {
   cursor: pointer;
  }
  
  </style>

