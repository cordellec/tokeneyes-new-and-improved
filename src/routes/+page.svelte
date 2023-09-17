<script>
	function disableRightClick(event) {
		event.preventDefault();
	}
</script>

<div class="text-center mt-8">
	<h1 class="custom-font text-4xl">CURRENTLY MINTING</h1>
</div>

<section class="grid grid-cols-2 md:grid-cols-4 gap-4 mx-auto max-w-screen-lg pt-8">
	<div class="flex items-center justify-center hover:opacity-80 cursor-pointer">
		<img
			class="h-auto max-w-full rounded-lg"
			src="../images/ETHEREUM.png"
			alt=""
			on:contextmenu={disableRightClick}
		/>
	</div>

	<div class="flex items-center justify-center hover:opacity-80 cursor-pointer">
		<img
			class="h-auto max-w-full rounded-lg"
			src="../images/BASE.png"
			alt=""
			on:contextmenu={disableRightClick}
		/>
	</div>

	<div class="flex items-center justify-center hover:opacity-80 cursor-pointer">
		<img
			class="h-auto max-w-full rounded-lg"
			src="../images/RIPPLE.png"
			alt=""
			on:contextmenu={disableRightClick}
		/>
	</div>

	<div class="flex items-center justify-center hover:opacity-80 cursor-pointer">
		<img
			class="h-auto max-w-full rounded-lg"
			src="../images/SOLANA.png"
			alt=""
			on:contextmenu={disableRightClick}
		/>
	</div>
</section>
