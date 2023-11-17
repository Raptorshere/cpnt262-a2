<script>
	import '../app.postcss';
	import { AppShell, AppBar } from '@skeletonlabs/skeleton';
</script>

<AppShell>
	<AppBar>
		<svelte:fragment slot="header"></svelte:fragment>
	</AppBar>
	<svelte:fragment slot="header"></svelte:fragment> -->
	(sidebarLeft) -->
	<!-- <svelte:fragment slot="sidebarRight">Hello World</svelte:fragment>
	<svelte:fragment slot="pageHeader"><h1>Fresh Aroma</h1></svelte:fragment>
	<!-- Router Slot
	<slot />
	<!-- ---- / ---- -->
	<svelte:fragment slot="pageFooter">&copy; Copyright 2023 | Kevin Fula	</svelte:fragment>
	<svelte:fragment slot="footer">Footer</svelte:fragment>
</AppShell> -->
<!-- App Shell
<AppShell>
	<svelte:fragment slot="header">
		<!-- App Bar -->
		<AppBar>
			<svelte:fragment slot="lead">
			<h1 class="text-center">Fresh Aroma</h1>
				<strong class="text-xl uppercase">Skeleton</strong>
			</svelte:fragment>
			<svelte:fragment slot="trail">
				<!--TODO: This is where the right side of the navigation is-->
				<a
					class="btn btn-sm variant-ghost-surface"
					href="/"
					target="_blank"
					rel="noreferrer"
				>
					Discord
				</a>
				<a
					class="btn btn-sm variant-ghost-surface"
					href="/"
					target="_blank"
					rel="noreferrer"
				>
					Twitter
				</a>
				<a
					class="btn btn-sm variant-ghost-surface"
					href="/"
					target="_blank"
					rel="noreferrer"
				>
					GitHub
				</a>
			</svelte:fragment>
		</AppBar>
	</svelte:fragment>
	<slot />
</AppShell>
