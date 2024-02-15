<script>
	import Button from "$lib/components/ui/button/button.svelte";
	import { ArrowRight } from "lucide-svelte";

</script>
<div class="bg-[#1e1919]">
    <div class="text-white text-center pt-[72px] max-w-[777px] mx-auto">
        <h1 class="text-3xl md:text-6xl">Securely collaborate on your content anywhere.</h1>
        <p class="text-sm md:text-lg mt-5">Lorem ipsum dolor sit amet consectetur adipisicing elit. Facere at cum delectus libero, nesciunt ducimus error possimus voluptates unde minima eveniet neque repellat ipsa, quasi vitae in sequi inventore. Eum!</p>
        <Button class="p-6 text-black font-semibold mt-10">Get started now <ArrowRight class="w-5 h-5"/> </Button>
    </div>
    <video class="mt-10" autoplay playsinline loop muted>
		<track kind="captions" />
		<source
			src="https://aem.dropbox.com/cms/content/dam/dropbox/warp/en-us/dropbox/dbx1-hero-1920x1080.mp4"
			type="video/mp4"
		/>
	</video>
</div>