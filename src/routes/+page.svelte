<script>
	function disableRightClick(event) {
		event.preventDefault();
	}
</script>

<!--
<div class="grid grid-cols-2 gap">
    <div class="col-start-1 flex flex-col justify-center items-center">
        <img src="../images/baselogo.png" alt="Skeleton Logo" class="w-56 mt-16" />
    </div>
    <div class="col-start-2 flex flex-col justify-center">
        <h2 class="max-w-6xl whitespace-wrap mr-6" id="nonherosection">
            AN EXCLUSIVE BASE CHAIN PROJECT
        </h2>
    </div>
</div>
-->

<div class="text-center mt-20">
	<h1 class="custom-font text-4xl m-4">CURRENTLY MINTING</h1>
</div>

<section
	class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 xl:grid-cols-4 gap-4 mx-auto m-4 max-w-screen-lg pt-8"
>
	<!-- Image 1 -->
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

	<!-- Repeat this structure for each image -->

	<!-- Image 2 -->
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

	<!-- Image 3 -->
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

	<!-- Image 4 -->
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

	<!-- Image 5 -->
	<div class="flex items-center justify-center hover:opacity-80 cursor-pointer">
		<a href="/chainlink">
			<img
				class="h-auto max-w-full rounded-lg"
				src="../images/CHAINLINK.png"
				alt=""
				on:contextmenu={disableRightClick}
			/>
		</a>
	</div>

	<!-- Image 6 -->
	<div class="flex items-center justify-center hover:opacity-80 cursor-pointer">
		<a href="/tron">
			<img
				class="h-auto max-w-full rounded-lg"
				src="../images/TRON.png"
				alt=""
				on:contextmenu={disableRightClick}
			/>
		</a>
	</div>

	<!-- Image 7 -->
	<div class="flex items-center justify-center hover:opacity-80 cursor-pointer">
		<a href="/avalanche">
			<img
				class="h-auto max-w-full rounded-lg"
				src="../images/AVALANCHE.png"
				alt=""
				on:contextmenu={disableRightClick}
			/>
		</a>
	</div>

	<!-- Image 8 -->
	<div class="flex items-center justify-center hover:opacity-80 cursor-pointer">
		<a href="/quant">
			<img
				class="h-auto max-w-full rounded-lg"
				src="../images/QUANT.png"
				alt=""
				on:contextmenu={disableRightClick}
			/>
		</a>
	</div>
</section>
