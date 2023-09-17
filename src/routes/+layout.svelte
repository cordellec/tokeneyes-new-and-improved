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
				<a href="/" class="text-xl uppercase custom-font">TOKENEYES LABS</a>
			</svelte:fragment>

			<svelte:fragment slot="trail">
				<a
					class="btn btn-sm variant-ghost-primary custom-font"
					href="/"
					target="_blank"
					rel="noreferrer"
				>
					NFT'S
				</a>
				<a
					class="btn btn-sm variant-ghost-primary custom-font"
					href="/"
					target="_blank"
					rel="noreferrer"
				>
					MERCH
				</a>
				<a
					class="btn btn-sm variant-ghost-primary custom-font"
					href="/about"
					target=""
					rel="noreferrer"
				>
					ABOUT
				</a>
				<div class="hidden sm:block">
					<LightSwitch />
				</div>
			</svelte:fragment>
		</AppBar>
	</svelte:fragment>
	<!-- Page Route Content -->
	<slot />

	<svelte:fragment slot="pageFooter">
		<div class="flex items-center justify-center mb-4 space-x-4 sm:space-x-8 md:space-x-12">
			<!-- Add classes to center the images vertically and horizontally -->
			<a
				href="https://discord.com/invite/TwVywVhpfp"
				target="_blank"
				rel="noreferrer"
				class="flex items-center justify-center"
			>
				<img src="../images/discord512px.png" alt="" class="w-15 h-10 sm:w-15 sm:h-10" />
			</a>

			<a
				href="https://twitter.com/tokeneyeslabs"
				target="_blank"
				rel="noreferrer"
				class="flex items-center justify-center"
			>
				<img src="../images/twitter512px.png" alt="" class="w-10 h-6 sm:w-18 sm:h-10" />
			</a>

			<a
				href="https://opensea.io/collection/tokeneyes"
				target="_blank"
				rel="noreferrer"
				class="flex items-center justify-center"
			>
				<img src="../images/opensea512px.png" alt="" class="w-8 h-6 sm:w-12 sm:h-10" />
			</a>
		</div>
	</svelte:fragment>
</AppShell>
