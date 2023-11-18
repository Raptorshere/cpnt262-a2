<script>
	import '../app.postcss';
	import { AppShell, AppBar, LightSwitch} from '@skeletonlabs/skeleton'
	// import Page from './+page.svelte';
	import about from "../lib/about/+page.svelte"
</script>
<!--I had a hard time making sense of why the code was not importing up top here and displaying the "About" page-->
	<AppShell>
		<svelte:fragment slot="header">
			<!-- <LightSwitch /> -->
<AppBar>
	<svelte:fragment slot="lead"><LightSwitch /></svelte:fragment>
	<a href="http://localhost:5173/" class="text-3xl uppercase"><strong><span class="bg-gradient-to-br from-blue-500 to-cyan-300 bg-clip-text text-transparent box-decoration-clone">Fresh Aroma</span></strong></a>
	<svelte:fragment slot="trail"><a class="btn btn-md variant-filled-secondary" href="/gallery">Gallery</a><a
	class="btn btn-md variant-filled-secondary"
	href="/about"
>About</a></svelte:fragment>
	<svelte:fragment slot="headline"><h3>It only makes scents</h3></svelte:fragment>
</AppBar>
  </svelte:fragment>
		<!-- <svelte:fragment slot="sidebarLeft">Sidebar Left</svelte:fragment> -->
		<slot />
		<!-- ---- / ---- -->
	<svelte:fragment slot="pageFooter">&copy; Copyright 2023 | Kevin Fula</svelte:fragment>
	<svelte:fragment slot="footer"><em>SkeletonUI</em></svelte:fragment>
	</AppShell>
	
	<slot />

	

	