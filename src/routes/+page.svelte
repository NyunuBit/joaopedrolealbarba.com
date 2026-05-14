<script lang="ts">
	import Video from "$lib/assets/xwrzm.mp4";
	import Img from "$lib/assets/7x846.png";
</script>

<div class="w-full flex-col gap-2 flex p-5 justify-center items-center">
	<p class="text-2xl italic text-white/50">
		joão pedro leal marba (eu escrevi errado).
	</p>
	<div class="flex justify-center items-center flex-col lg:flex-row gap-2">
		<div
			style="background-image: url('{Img}');"
			class="aspect-square bg-contain md:w-auto w-screen p-5 bg-no-repeat"
		>
			<p class="text-shadow-2xs max-w-152 text-4xl w-screen font-black">
				Esse é joão pedro leal marba
			</p>
		</div>
		<video src={Video} loop autoplay></video>
	</div>
</div>
<div class="bottom-0 w-full p-2 flex justify-between items-center">
	<a
		href="https://github.com/NyunuBit/joaopedrolealbarba.com"
		class="underline text-purple-500 hover:text-purple-300 font-bold duration-200"
		>Source Code</a
	>
	<p>by Nyunu</p>
</div>
