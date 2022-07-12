<script>
	import Hamburger from 'svelte-hamburger';
	import { slide } from 'svelte/transition';
	let open = false;
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

		<Hamburger class="md:hidden" duoLine={false} {open} on:click={() => (open = !open)} />

		<div class="hidden md:flex md:gap-x-4 lg:gap-x-8">
			<!-- for large screens -->
			<a class="font-bold underline-offset-8 hover:text-[#565656] hover:underline" href="/">Home</a>
			<a class="font-bold underline-offset-8 hover:text-[#565656] hover:underline" href="/members"
				>Members</a
			>
			<a class="font-bold underline-offset-8 hover:text-[#565656] hover:underline" href="/partners"
				>Our Partners</a
			>
			<a
				class="font-bold underline-offset-8 hover:text-[#565656] hover:underline"
				href="/getinvolved">Get Involved</a
			>
			<a class="font-bold underline-offset-8 hover:text-[#565656] hover:underline" href="/contact"
				>Contact Us</a
			>
		</div>
	</div>

	{#if open}
		<!-- dropdown menu -->
		<div transition:slide={{ duration: 800 }} class="absolute w-screen bg-[#ffc8b6] md:hidden">
			<div class="container flex flex-col gap-4 pt-4 pb-8 text-right">
				<div>
					<a class="fit font-bold underline-offset-8 hover:text-[#565656] hover:underline" href="/"
						>Home</a
					>
				</div>
				<div>
					<a
						class="font-bold underline-offset-8 hover:text-[#565656] hover:underline"
						href="/members">Members</a
					>
				</div>
				<div>
					<a
						class="font-bold underline-offset-8 hover:text-[#565656] hover:underline"
						href="/partners">Our Partners</a
					>
				</div>
				<div>
					<a
						class="font-bold underline-offset-8 hover:text-[#565656] hover:underline"
						href="/getinvolved">Get Involved</a
					>
				</div>
				<div>
					<a
						class="font-bold underline-offset-8 hover:text-[#565656] hover:underline"
						href="/contact">Contact Us</a
					>
				</div>
			</div>
		</div>
	{/if}
</div>
