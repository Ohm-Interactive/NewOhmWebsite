<script>
    import "../app.css"
    import Navbar from "../lib/Navbar.svelte"
    import {page} from '$app/stores'
	import Footer from "$lib/Footer.svelte";
</script>
{#if $page.status !== 404}
    <Navbar></Navbar>
{/if}
<main>
    <slot></slot>
</main>
<Footer></Footer>