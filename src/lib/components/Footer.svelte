<script>
	import fb from '$lib/fb.png';
	import lk from '$lib/lk.png';
	import twitter from '$lib/twitter.png';
	import insta from '$lib/insta.png';
	import tiktok from '$lib/tiktok.png';
</script>

<div class="w-full bg-[#ffc8b6] py-10 px-8">
	<div class="container mx-auto grid grid-cols-1 gap-y-4 md:grid-cols-2">
		<div>
			<!-- left side / top-->
			<div class="flex gap-4">
				<a href="https://www.instagram.com/bridgingseas/"
					><img src={insta} alt="instagram" class="h-12 w-12" /></a
				>
				<a href="https://www.facebook.com/bridgingseas/"
					><img src={fb} alt="facebook" class="h-12 w-12" /></a
				>
				<a href="https://twitter.com/BridgingSeas"
					><img src={twitter} alt="twitter" class="h-12 w-12" /></a
				>
				<a href="https://www.linkedin.com/company/bridging-seas/"
					><img src={lk} alt="linkedln" class="h-12 w-12" /></a
				>

				<a href="https://www.tiktok.com/@bridgingseas?"
					><img src={tiktok} alt="tiktok" class="h-12 w-12" /></a
				>
			</div>
		</div>

		<div>
			<!-- right side / bottom-->
			<div>
				<p class="font-bold">Contact Us</p>
				<a href="mailto:bridgingseasnyc@gmail.com">bridgingseasnyc@gmail.com</a>
			</div>
		</div>
	</div>
</div>
