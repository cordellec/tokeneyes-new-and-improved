<script>
	function disableRightClick(event) {
		event.preventDefault();
	}
</script>

<div class="grid grid-cols-2gap">
	<div class="col-start-1 flex flex-col justify-center items-center">
		<img src="../images/baselogo.png" alt="Skeleton Logo" class="w-56 mt-16" />
	</div>
	<div class="col-start-2 flex flex-col justify-center">
		<h2 class="max-w-6xl whitespace-wrap mr-6" id="nonherosection">
			AN EXCLUSIVE BASE CHAIN PROJECT
		</h2>
	</div>
</div>

<div class="text-center mt-36">
	<h1 class="custom-font text-4xl">CURRENTLY MINTING</h1>
</div>

<section class="grid grid-cols-2 md:grid-cols-4 gap-4 mx-auto max-w-screen-lg pt-8">
	<div class="flex items-center justify-center hover:opacity-80 cursor-pointer">
		<a href="/ethereum">
			<img
				class="h-auto max-w-full rounded-lg"
				src="../images/ETHEREUM.png"
				alt=""
				on:contextmenu={disableRightClick}
			/>
		</a>
	</div>

	<div class="flex items-center justify-center hover:opacity-80 cursor-pointer">
		<a href="/base">
			<img
				class="h-auto max-w-full rounded-lg"
				src="../images/BASE.png"
				alt=""
				on:contextmenu={disableRightClick}
			/>
		</a>
	</div>

	<div class="flex items-center justify-center hover:opacity-80 cursor-pointer">
		<a href="/ripple">
			<img
				class="h-auto max-w-full rounded-lg"
				src="../images/RIPPLE.png"
				alt=""
				on:contextmenu={disableRightClick}
			/>
		</a>
	</div>

	<div class="flex items-center justify-center hover:opacity-80 cursor-pointer">
		<a href="/solana">
			<img
				class="h-auto max-w-full rounded-lg"
				src="../images/SOLANA.png"
				alt=""
				on:contextmenu={disableRightClick}
			/>
		</a>
	</div>
</section>
