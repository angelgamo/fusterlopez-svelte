<script lang="ts">
	import '../app.css';
	import '$lib/fonts/fonts.css';

	let { children } = $props();
</script>

<div class="flex justify-between absolute w-full max-w-[1600px] p-5 text-Secundario *:*:hover:text-[var(--Principal)] text-white">
	<div class="flex gap-x-2 *:pr-2 divide-x-1 divide-solid divide-white">
		<a href="_blank">Fuster & López</a>
		<a href="_blank">Empresas</a>
		<a href="_blank">Conozenos</a>
		<a href="_blank">Fundación</a>
		<a href="_blank">Proyectos</a>
		<a href="_blank">Contacto</a>
	</div>
	<div class="flex gap-x-2 *:pr-3 divide-x-1 divide-solid">
		<a href= "mailto: fusterandlopez@fusterandlopez.com">fusterandlopez@fusterandlopez.com</a>
		<a href="tel:34943202293">+34 943 20 22 93</a>
	</div>
</div>

{@render children()}

<div class="py-20 px-8 flex flex-col gap-3 relative text-white">
    <div class="absolute inset-0 left-[-33vw] right-[-33vw] z-[-1] bg-[rgb(16,7,9)] bg-[url($lib/assets/images/pattern.png)]"></div>
	<div class="m-auto flex flex-col items-center *:text-[var(--Principal)]">
		<enhanced:img src="$lib/assets/images/Logo_FB.png?grayscale&w=150" alt="An alt text"/>
		<a class="text-Enfasis" href= "mailto: fusterandlopez@fusterandlopez.com">fusterandlopez@fusterandlopez.com</a>
		<a class="text-Enfasis" href="tel:34943202293">+34 943 20 22 93</a>
	</div>
</div>
<div class="bg-[var(--Principal)] p-2 w-screen absolute left-0">
	<p class="text-Texto text-center text-white">Todos los derechos reservados ©Fuster&Lopez 2025 </p>
</div>