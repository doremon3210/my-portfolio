<script>
	import Navbar from '$lib/components/Navbar.svelte';
	import Hero from '$lib/components/Hero.svelte';
	import About from '$lib/components/About.svelte';
	import Work from '$lib/components/Work.svelte';
	import Hobbies from '$lib/components/Hobbies.svelte';
	import Footer from '$lib/components/Footer.svelte';
</script>

<Navbar />

<main>
	<div id="hero">
		<Hero />
	</div>

	<div id="about">
		<About />
	</div>

	<div id="work">
		<Work />
	</div>

	<div id="hobbies">
		<Hobbies />
	</div>

	<div id="footer">
		<Footer />
	</div>
</main>
