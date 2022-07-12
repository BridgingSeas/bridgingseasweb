<script>
	import Hero from '$lib/components/Hero.svelte';
	import fortnite from '$lib/fortnite.jpg';
	import fallguys from '$lib/fallguys.jpg';

	import jhope from '$lib/bts/jhope.jpg';
	import jimin from '$lib/bts/jimin.jpg';
	import jin from '$lib/bts/jin.jpg';
	import jungkook from '$lib/bts/jungkook.jpg';
	import rm from '$lib/bts/rm.jpg';
	import suga from '$lib/bts/suga.jpg';
	import v from '$lib/bts/v.jpg';
</script>

<Hero />

<div class="container mb-20 grid grid-cols-2 gap-x-8">
	<div>
		<!-- left -->
		<p class="font-serif text-4xl font-bold">Connect with your roots</p>

		<p>
			Lorem ipsum dolor sit amet consectetur adipisicing elit. Dolores rem neque, corrupti,
			explicabo, exercitationem sunt ducimus veritatis officiis dignissimos at molestias reiciendis
			nisi adipisci assumenda voluptate saepe laboriosam dicta quis id possimus provident tempore
			dolor. Eos, exercitationem repudiandae ad sequi reprehenderit temporibus id ex repellat nulla
			dolores minima maiores deleniti natus, excepturi dignissimos optio laborum vero veritatis
			ullam laudantium. Numquam omnis suscipit quia ipsa. Ut consectetur sint laudantium, omnis
			quasi quam rerum assumenda aliquam quas. Ad exercitationem ea magni nesciunt sunt, debitis
			tenetur reiciendis distinctio dolorum, beatae minima veniam, excepturi maiores quae
			perspiciatis voluptas. Perspiciatis a rerum illum tenetur in!
		</p>
	</div>

	<div>
		<!-- right -->
		<img alt="fortnite" src={fortnite} />
	</div>
</div>

<div class="container mb-20 grid grid-cols-2 gap-x-8">
	<div>
		<!-- left -->
		<img alt="fallguys" src={fallguys} />
	</div>

	<div>
		<!-- right -->
		<p class="font-serif text-4xl font-bold">
			The messages seen <span class="underline">'round</span> the world
		</p>

		<p>
			Lorem ipsum dolor sit amet consectetur adipisicing elit. Dolores rem neque, corrupti,
			explicabo, exercitationem sunt ducimus veritatis officiis dignissimos at molestias reiciendis
			nisi adipisci assumenda voluptate saepe laboriosam dicta quis id possimus provident tempore
			dolor. Eos, exercitationem repudiandae ad sequi reprehenderit temporibus id ex repellat nulla
			dolores minima maiores deleniti natus, excepturi dignissimos optio laborum vero veritatis
			ullam laudantium. Numquam omnis suscipit quia ipsa. Ut consectetur sint laudantium, omnis
			quasi quam rerum assumenda aliquam quas. Ad exercitationem ea magni nesciunt sunt, debitis
			tenetur reiciendis distinctio dolorum, beatae minima veniam, excepturi maiores quae
			perspiciatis voluptas. Perspiciatis a rerum illum tenetur in!
		</p>
	</div>
</div>

<div class="container mb-20">
	<div>
		<p class="pb-4 text-center font-serif text-4xl font-bold">
			latest on <a class="underline" href="https://www.instagram.com/bridgingseas/">@bridgingseas</a
			>
		</p>

		<div class="grid grid-cols-3 place-items-center gap-2">
			<img width="500" height="500" alt="jhope" src={jhope} />
			<img width="500" height="500" alt="jimin" src={jimin} />
			<img width="500" height="500" alt="jin" src={jin} />
			<img width="500" height="500" alt="jungkook" src={jungkook} />
			<img width="500" height="500" alt="rm" src={rm} />
			<img width="500" height="500" alt="suga" src={suga} />
			<img width="500" height="500" alt="v" src={v} />
		</div>
	</div>
</div>
