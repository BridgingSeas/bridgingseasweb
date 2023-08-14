<script>
	import Hero from '$lib/components/Hero.svelte';
	import Card from '$lib/components/Card.svelte';

	import group from '$lib/img/photos/group.png?w=500;700;896&webp&srcset';
	import picnic from '$lib/img/photos/picnic.png?w=500;700;896&webp&srcset';

	import unity from '$lib/img/graphics/unity.png?w=500;700;896&webp&srcset';
	import app from '$lib/img/graphics/appreciation.png?w=500;700;896&webp&srcset';
	import culture from '$lib/img/graphics/culture.png?w=500;700;896&webp&srcset';
	import chart from '$lib/img/graphics/chart.jpg?w=500;700;896&webp&srcset';
	import pie from '$lib/img/graphics/pie.jpg?w=500;700;896&webp&srcset';

</script>





<Hero />
<div class="container mb-20 grid grid-cols-1 gap-x-8 pt-20 xl:grid-cols-2">
	<div>
		<!-- left / top -->
		<p class="font-serif text-4xl font-bold">Connect with your roots</p>

		<p class="pt-4 text-lg">
			Bridging Seas is a youth-led global organization that aims to unify the Asian diaspora. Our goal is to connect high schoolers from around the world by creating a platform for them to learn about each other's cultures and unique experiences. We envision a more compassionate, understanding world where students embrace their roots and different lifestyles through direct communication with international friends.
		</p>
	</div>

	<div class="pt-10 xl:pt-0">
		<!-- right / bottom -->
		<img type="image/webp" alt="group" srcset={group} />
	</div>
</div>

<div class="container mb-20 grid grid-cols-1 gap-x-8 xl:grid-cols-2">
	<div>
		<!-- left / top -->
		<img type="image/webp" alt="picnic" srcset={picnic} />
	</div>

	<div class="pt-10 xl:pt-0">
		<!-- right / bottom -->
		<p class="font-serif text-4xl font-bold">
			The messages seen 'round the world
		</p>

		<p class="pt-4 text-lg">
			Want to make friends across the world? We got you. Bridging Seas offers a pen pal program. Asian students all over the word regardless of nationality will be matched with a pen pal of the same ethnicity. Make new friends and get to know a world outside of your own!
		</p>
	</div>
</div>

<div class="container grid place-items-center">
	<p class="text-[50px] font-bold font-serif">Our Impact</p>
</div>

<div class="container mb-20 grid grid-cols-1 gap-x-8 xl:grid-cols-2">
	<div>
		<!-- left / top -->
		<img type="image/webp" alt="chart" srcset={chart} />
	</div>
	<div>
	<!-- right / top -->
	<img type="image/webp" alt="pie" srcset={pie} />
	</div>
</div>

<div class="container grid place-items-center">
	<p class="text-[50px] font-bold font-serif">Our 3 Pillars</p>
	<p class="pb-5 text-[20px]">Learn More About Our Values</p>
</div>
<div class="container mb-20 h-min grid grid-cols-1	gap-y-8 gap-x-8 xl:grid-cols-3">
	<!-- <div class="grid grid-rows-2 pb-5">
		<img src={app} alt="appreciation" />
		<p class="rounded-b-lg bg-[#FDF4E3] pr-5 pl-5 pt-5 pb-5 text-center font-semibold">
			Bridging Seas believes culture represents a vision of life that follows us from our upbringings to our futures and aspirations. Culture is the core of who we are and connects us with those who share the same culture. Recognizing the potential for culture to unify the Asian diaspora, Bridging Seas aims to emphasize the discussion of culture with all youth, connecting students from around the world closer to their cultural roots and encouraging them to embrace the diversity of culture around them through pen palling
		</p>
	</div> -->
	<div class="">
		<Card alt="culture" image={culture}  --bgcolor="rgb(255, 192, 180)">
			<p class="text-[30px] font-bold ">Culture</p>
			<p class="text-[1vw]">Bridging Seas recognizes that <strong>culture</strong> is the core of who we are and connects us with those who share the same <strong>culture</strong>. Tapping into the <strong>culture</strong> of our youth, we encourage students from around the world to embrace the diversity of their <strong>cultural</strong> roots through pen-palling.</p>
		</Card>
	</div>
	<div>
		<Card alt="appreciation" image={app} --bgcolor="rgb(255, 226, 211)">
			<p class="text-[30px] font-bold ">Appreciation</p>
			<p class="text-[1vw]">As youth ourselves, the Bridging Seas team offers a safe platform for students to not only <strong>appreciate</strong> their culture through exchange with students who share the same roots, but also a place to discover how their culture is diverse, adaptable, and eternally changing.</p>
		</Card>
	</div>
	<div>
		<Card alt="community" image={unity} --bgcolor="rgb(255, 192, 180)">
			<p class="text-[30px] font-bold ">Community</p>
			<p class="text-[1vw]">Bridging Sea’s foremost mission is to foster a <strong>community</strong> for our students to feel comfortable in sharing their culture. Through monthly meetings and <strong>community</strong> corners, we aim to make our students feel supported and heard in our <strong>community</strong> as they grow in their cultural exploration.</p>
		</Card>
	</div>

	<!-- <div class="grid grid-rows-2 pb-5">
		<img src={unity} alt="unity" />
		<p class="rounded-b-lg bg-[#FDF4E3] pr-5 pl-5 pt-5 pb-5 text-center font-semibold">
			As youth ourselves, the Bridging Seas team knows too well the constant struggle to love 
			and appreciate our nuanced and diverse cultures. Bridging Seas is a safe platform for students to not only appreciate 
			their cultural roots through exchange with students that share those roots, but also a place to discover 
			how their culture is diverse, adaptable, and changing all the time when they speak with students that even though share the same ethnicity as them, 
			live in different parts of the world and experience culture in a completely different way.
		</p>
	</div>
	<div class="grid grid-rows-2 pb-5 place-items-center ">
		<img class=":w-4/5 md:h-4/5" src={culture} alt="culture" />
		<p class="rounded-b-lg bg-[#FDF4E3] pr-5 pl-5 pt-5 pb-5 text-center font-semibold md:w-4/5">
			Bridging Sea’s foremost mission is to create safe spaces for our students to feel comfortable sharing their culture with others. Learning to appreciate our culture can be a hard struggle. We aim to make our students feel supported and heard in our community as they grow in their cultural exploration. Through our monthly meetings and community corners, we cultivate that safe space for our youth to come together and make friends that will become a part of their family. 
		</p>
	</div>-->
	
	
</div>

<div class="container mb-20">
	<div>
		<p class="pb-10 text-center font-serif text-4xl font-bold">
			latest on <a class="underline" href="https://www.instagram.com/bridgingseas/">@bridgingseas</a
			>
		</p>

		<div class="grid grid-cols-1 xl:grid-cols-3 place-items-center gap-2">
			<a href="https://www.instagram.com/p/Cqx422xOo4H/?utm_source=ig_web_copy_link&igshid=MzRlODBiNWFlZA==">
				<img width="500" height="500"  src="https://cdn.discordapp.com/attachments/981730764469182485/1109293548253220904/340503369_457922373174194_5958789526327651558_n.jpg"  alt="1"/>
			</a>
			<a href="https://www.instagram.com/p/CnvD8wSLl3Z/?utm_source=ig_web_copy_link&igshid=MzRlODBiNWFlZA==">
				<img width="500" height="500"  src="https://cdn.discordapp.com/attachments/981730764469182485/1109308149644668978/326198208_1228542168081391_5097486918071226158_n.jpg" alt="2"/>
			</a>
			<a href="https://www.instagram.com/p/ChsJnw2Oq_K/?utm_source=ig_web_copy_link">
				<img width="500" height="500"  src="https://cdn.discordapp.com/attachments/536643425827815424/1071251322487181402/325295646_1597065234097929_5878692940469965849_n.jpg" alt="3"/>
			</a>
			
		</div>
	</div>
</div>
