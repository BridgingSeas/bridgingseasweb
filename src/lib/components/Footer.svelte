<script>
	import fb from '$lib/img/logos/socials/facebook.png?w=500;700;896&webp&srcset';
	import lk from '$lib/img/logos/socials/linkedin.png?w=500;700;896&webp&srcset';
	import twitter from '$lib/img/logos/socials/twitter.png?w=500;700;896&webp&srcset';
	import insta from '$lib/img/logos/socials/instagram.png?w=500;700;896&webp&srcset';
	import tiktok from '$lib/img/logos/socials/tiktok.png?w=500;700;896&webp&srcset';
</script>

<div class="w-full bg-[#ffc8b6] py-10 px-">
	<div class="container mx-auto grid grid-cols-1 gap-y-4 md:grid-cols-2">
		<div>
			<!-- left side / top-->
			<div class="flex gap-4">
				<a href="https://www.instagram.com/bridgingseas/"
					><img type="image/webp" srcset={insta} alt="instagram" class="h-12 w-12" /></a
				>
				<a href="https://www.facebook.com/bridgingseas/"
					><img type="image/webp" srcset={fb} alt="facebook" class="h-12 w-12" /></a
				>
				<a href="https://twitter.com/BridgingSeas"
					><img type="image/webp" srcset={twitter} alt="twitter" class="h-12 w-12" /></a
				>
				<a href="https://www.linkedin.com/company/bridging-seas/"
					><img type="image/webp" srcset={lk} alt="linkedln" class="h-12 w-12" /></a
				>

				<a href="https://www.tiktok.com/@bridgingseas?"
					><img type="image/webp" srcset={tiktok} alt="tiktok" class="h-12 w-12" /></a
				>
			</div>
		</div>

		<div>
			<!-- right side / bottom-->
			<div>
				<p class="font-bold">Contact Us</p>
				<a class="hover:text-[#565656]" href="mailto:bridgingseasnyc@gmail.com"><u>bridgingseasnyc@gmail.com</u></a>
			</div>
		</div>
	</div>
</div>
