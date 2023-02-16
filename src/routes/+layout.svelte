<script>
	import SocialHandle from "$lib/social-handle.svelte";
import Navbar from "../lib/navbar.svelte";
	import "../styles/global.css"
</script>

<header><Navbar/></header>
<main style="background: #0A192F;"><SocialHandle/><slot></slot></main>
<footer></footer>

<style>
</style>