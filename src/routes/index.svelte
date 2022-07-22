<script>
	import Hero from '$lib/components/Hero.svelte';

	import bridge from '$lib/bridge.png';
	import sponge from '$lib/sponge.png';

	import jhope from '$lib/bts/jhope.jpg';
	import jimin from '$lib/bts/jimin.jpg';
	import jin from '$lib/bts/jin.jpg';
	import jungkook from '$lib/bts/jungkook.jpg';
	import rm from '$lib/bts/rm.jpg';
	import suga from '$lib/bts/suga.jpg';
	import v from '$lib/bts/v.jpg';
	import unity from '$lib/unity.png';
	import app from '$lib/appreciation.png';
	import culture from '$lib/culture.png';
</script>

<Hero />

<div class="container mb-20 grid grid-cols-1 gap-x-8 pt-20 xl:grid-cols-2">
	<div>
		<!-- left / top -->
		<p class="font-serif text-4xl font-bold">Connect with your roots</p>

		<p class="pt-4">
			Lorem ipsum dolor sit amet consectetur adipisicing elit. Dolores rem neque, corrupti,
			explicabo, exercitationem sunt ducimus veritatis officiis dignissimos at molestias reiciendis
			dolor. Eos, exercitationem repudiandae ad sequi reprehenderit temporibus id ex repellat nulla
			dolores minima maiores deleniti natus, excepturi dignissimos optio laborum vero veritatis
			ullam laudantium. Numquam omnis suscipit quia ipsa. Ut consectetur sint laudantium, omnis
			quasi quam rerum assumenda aliquam quas. Ad exercitationem ea magni nesciunt sunt, debitis
			tenetur reiciendis distinctio dolorum, beatae minima veniam, excepturi maiores quae
			perspiciatis voluptas. Perspiciatis a rerum illum tenetur in!
		</p>
	</div>

	<div class="pt-10 xl:pt-0">
		<!-- right / bottom -->
		<img alt="bridge" src={bridge} />
	</div>
</div>

<div class="container mb-20 grid grid-cols-1 gap-x-8 xl:grid-cols-2">
	<div>
		<!-- left / top -->
		<img alt="sponge" src={sponge} />
	</div>

	<div class="pt-10 xl:pt-0">
		<!-- right / bottom -->
		<p class="font-serif text-4xl font-bold">
			The messages seen <span class="underline">'round</span> the world
		</p>

		<p class="pt-4">
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

<div class="container mb-20 grid grid-cols-1 grid-rows-2 gap-x-8 xl:grid-cols-3">
	<div>
		<img src={app} alt="appreciation" />
	</div>

	<div>
		<img src={unity} alt="unity" />
	</div>
	<div>
		<img src={culture} alt="culture" />
	</div>
	<div>
		<p class="rounded-b-lg bg-[#FDF4E3] pr-5 pl-5 pt-5 pb-5 text-center font-semibold">
			Not only do we encouraging the act of embracing our cultures, we want people to appreciate
			each others’ cultures, including overlapping similaries and differences. It is through
			appreciating the small specific nuances of shared culture through pen-palling that our pairs
			learn to love and accept their cultures even more.
		</p>
	</div>
	<div>
		<p class="rounded-b-lg bg-[#FDF4E3] pr-5 pl-5 pt-5 pb-5 text-center font-semibold">
			At Bridging Seas, one of our overarching goals is to cultivate a safe community space for
			youth to come together and make friends, not just with their pen-pals but with other pen-pal
			pairs too. Through monthly community corners and meetings, we aim to foster a long-lasting
			community that will always be there for our pen-pals.
		</p>
	</div>
	<div>
		<p class="rounded-b-lg bg-[#FDF4E3] pr-5 pl-5 pt-5 pb-5 text-center font-semibold">
			Our cultures represent visions of life that follow us from our upbringing to our future and
			aspirations. They are core to who we are and link us with others who share the same culture.
			Recognizing the potential for culture to unify the Asian diaspora, Bridging Seas aims to
			bridge this cultural gap through pen-palling and making new connections.
		</p>
	</div>
</div>

<div class="container mb-20">
	<div>
		<p class="pb-4 text-center font-serif text-4xl font-bold">
			latest on <a class="underline" href="https://www.instagram.com/bridgingseas/">@bridgingseas</a
			>
		</p>

		<div class="grid grid xl:grid-cols-3 place-items-center gap-2">
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
