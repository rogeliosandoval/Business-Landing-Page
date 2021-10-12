<script>
	import '../app.css';
	import Navbar from "$lib/components/navbar.svelte";
	import Footer from "$lib/components/footer.svelte";
</script>

<main class="bg-yellow-200 m-0 w-screen h-screen">
<Navbar />
<slot />
<Footer />
</main>
