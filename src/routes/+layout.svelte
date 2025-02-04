<!-- Google tag (gtag.js) -->
<!-- <script async src="https://www.googletagmanager.com/gtag/js?id=G-9NHVYZVMZV"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());

  gtag('config', 'G-9NHVYZVMZV');
</script>  -->
<script>
	import Header from '$lib/components/Header.svelte';
	import Footer from '$lib/components/Footer.svelte';
	import '../app.css';
</script>


<div class="flex min-h-screen flex-col">
	<div class="grow bg-[#faf8f6]">
		<Header />
		<slot />
	</div>
	<div class="grow-0">
		<Footer />
	</div>
</div>
