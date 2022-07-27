<script>
	import donate from '$lib/donate.png';
</script>

<div class="grid grid-cols-1 place-items-center bg-[#ffe2d3] xl:grid-cols-2">
	<div class="content-center text-center">
		<p class="pb-5 font-serif text-5xl sm:text-6xl">Donate</p>
		<p class="px-20 text-xl">
			Donations will go towards purchases to help us continue operations. This includes:
		</p>
		<ul class="list-inside list-disc text-xl">
			<li>maintaining our website</li>
			<li>applying for 501(c)(3) nonprofit status</li>
			<li>promotions to spread our mission</li>
		</ul>
		<br />
		<p class="px-20 text-xl">
			As a relatively new organization, we depend on your donations to continue helping connect the
			Asian diaspora. All extra funds will be donated to organizations or projects that help AAPI
			combat hate or assist other Asian countries to recover from COVID. Each donor can vote for
			which organization and project they’d like us to support. Additionally, the top 20 donors can
			choose to have their name displayed on our website as a token of our appreciation.
		</p>
		<a href="https://docs.google.com/forms/d/e/1FAIpQLSekyqAR9MnH7l_qNF2rdNjBucfvuXkMCIQlOw1Ryb81H3FzrA/viewform">
			<div
				class="mx-auto mt-10 max-w-fit rounded-md bg-[#e88073] px-8 py-2 text-xl text-sm text-[#fffffa] sm:mt-20 sm:text-base"
			>
				Contribute
			</div>
		</a>
	</div>
	<img src={donate} alt="donate" />
</div>
