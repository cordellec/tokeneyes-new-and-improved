<script>
	function disableRightClick(event) {
		event.preventDefault();
	}
</script>

<div class="grid grid-cols-1 md:grid-cols-2 gap-8 p-4 md:p-8 lg:p-12">
	<div class="flex justify-center items-center text-center">
		<img
			src="../images/EVMOS.png"
			alt="Skeleton Logo"
			class="w-96 mt-8 md:mt-16"
			on:contextmenu={disableRightClick}
		/>
	</div>
	<div class="flex flex-col justify-center lg:text-left">
		<!-- Add lg:text-left here -->
		<h2 id="hero" class="text-2xl md:text-3xl mb-4 md:mb-8 text-center lg:text-left">
			What are Tokeneyes?
		</h2>
		<p class="max-w-2xl text-center lg:text-left">
			<!-- Add lg:text-left here -->
			Tokeneyes Labs is the brainchild of Cordelle, a passionate advocate of web 3 and all things crypto.
			Having noticed the lack of originality and too much copy-and-paste in the web 3 world, Cordelle
			decided to inject some personality into the industry.
			<br /><br />
			In early 2022, he began drawing his favorite cryptocurrencies, giving them faces for fun, but soon
			forgot about them. Months later, he was struck with an idea - why not give all cryptocurrencies
			a unique personality? And that's how Tokeneyes Labs came to be.
			<br /><br />
			With Cordelle's passion and creativity at the helm, Tokeneyes Labs promises to bring a fresh perspective
			to the crypto world and add some much-needed personality to the industry.
		</p>
	</div>
	<div class="flex justify-center items-center text-center">
		<img
			src="../images/RIPPLE.png"
			alt="Skeleton Logo"
			class="w-96 mt-8 md:mt-0"
			on:contextmenu={disableRightClick}
		/>
	</div>
	<div class="flex flex-col justify-center lg:text-left">
		<!-- Add lg:text-left here -->
		<h2 id="hero" class="text-2xl md:text-3xl mb-4 md:mb-8 text-center lg:text-left">
			How can I get involved?
		</h2>
		<p class="max-w-2xl text-center lg:text-left">
			<!-- Add lg:text-left here -->
			Tokeneyes was created to be accessible and cherished by everyone, not limited to being just an
			NFT project. With options including shirts and prints to wear or display on your walls, you can
			choose how to enjoy Tokeneyes in a way that suits you.
			<br /><br />
			Whether or not you have a preferred cryptocurrency, finding a piece you love is a breeze because
			each one brings a distinct personality. Cordelle, the creator, is open to suggestions for future
			Tokeneyes pieces, so don't hesitate to let him know if you have any ideas for bringing your favorite
			crypto to life.
		</p>
	</div>
</div>
