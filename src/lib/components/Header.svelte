<script>
	import menuIcon from "$lib/hamburger.png"
</script>

<div class="sticky top-0 z-50 w-full bg-[#ffc8b6] py-4 drop-shadow-xl">
	<div class="container mx-auto flex items-center">
		<a href="/"
			><img
				src="https://assets.zyrosite.com/cdn-cgi/image/format=auto,w=224,fit=crop/m2Wgwzkj3GFqQPR0/Bridging-Seas-mePe9k6belSbvxM5.png"
				alt="logo"
			/></a
		>

		<div class="flex-grow" />


		<div class="md:hidden">
			<button>
			<img width="24" height="24" src={menuIcon} alt="open menu">
			</button>
		</div>


		<div class="hidden md:flex md:gap-x-4 lg:gap-x-8"> <!-- for large screens -->
			<a class="underline-offset-8 hover:text-[#565656] hover:underline" href="/">Home</a>
			<a class="underline-offset-8 hover:text-[#565656] hover:underline" href="/members">Members</a>
			<a class="underline-offset-8 hover:text-[#565656] hover:underline" href="/partners"
				>Our Partners</a
			>
			<a class="underline-offset-8 hover:text-[#565656] hover:underline" href="/getinvolved"
				>Get Involved</a
			>
			<a class="underline-offset-8 hover:text-[#565656] hover:underline" href="/contact"
				>Contact Us</a
			>
		</div>
	</div>
</div>
