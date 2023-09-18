<script>
	import '../app.postcss';
	import { AppShell, AppBar } from '@skeletonlabs/skeleton';

	// Floating UI for Popups
	import { computePosition, autoUpdate, flip, shift, offset, arrow } from '@floating-ui/dom';
	import { storePopup } from '@skeletonlabs/skeleton';
	storePopup.set({ computePosition, autoUpdate, flip, shift, offset, arrow });
	import { LightSwitch } from '@skeletonlabs/skeleton';
</script>

<!-- App Shell -->
<AppShell>
	<svelte:fragment slot="header">
		<!-- App Bar -->

		<AppBar>
			<svelte:fragment slot="lead">
				<a href="/" class="text-xl uppercase">TOKENEYES LABS</a>
			</svelte:fragment>

			<svelte:fragment slot="trail">
				<a class="btn btn-sm variant-ghost-primary" href="/" target="" rel="noreferrer"> NFT'S </a>
				<a class="btn btn-sm variant-ghost-primary" href="/about" target="" rel="noreferrer">
					ABOUT
				</a>
				<div class="sm:flex items-center space-x-4">
					<!-- Use flex and space-x to align items horizontally -->
					<LightSwitch />
				</div>
			</svelte:fragment>
		</AppBar>
	</svelte:fragment>
	<!-- Page Route Content -->
	<slot />

	<svelte:fragment slot="pageFooter">
		<div class="flex items-center justify-center mb-4 space-x-8 md:space-x-12 pt-2">
			<a
				href="https://discord.com/invite/TwVywVhpfp"
				target="_blank"
				rel="noreferrer"
				class="flex items-center justify-center"
			>
				<img src="../images/discordlogo.png" alt="" class="w-15 h-10" />
			</a>

			<a
				href="https://twitter.com/tokeneyeslabs"
				target="_blank"
				rel="noreferrer"
				class="flex items-center justify-center"
			>
				<img src="../images/twitterlogo.png" alt="" class="w-15 h-10" />
			</a>

			<a
				href="https://opensea.io/collection/tokeneyes"
				target="_blank"
				rel="noreferrer"
				class="flex items-center justify-center"
			>
				<img src="../images/opensealogo.png" alt="" class="w-15 h-10" />
			</a>
		</div>
	</svelte:fragment>
</AppShell>
