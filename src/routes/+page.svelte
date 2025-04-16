<script>
	import Titulo from "$lib/components/Titulo.svelte";

</script>
<h1>Welcome to SvelteKit</h1>
<p>Visit <a href="https://svelte.dev/docs/kit">svelte.dev/docs/kit</a> to read the documentation</p>

<Titulo></Titulo>

<style>

:global(*) {
  margin: 0;
  padding: 0;
  outline: 0;
  box-sizing: border-box;
}
@font-face{
    font-family: "Nunito";
    src: url(./styles/fonts/NunitoSans.ttf);
}

:global(body) {
 background: white;
 color: white ;
 -webkit-font-smoothing: antialiased;
}

:global(body, input, button) {
 font-size: 14px;
 font-family:"Nunito";
}

:global(button) {
 cursor: pointer;
}

</style>