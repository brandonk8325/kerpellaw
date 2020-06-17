<script>
	import Nav from '../components/Nav.svelte';
	import Footer from '../components/Footer.svelte';
	export let segment;
</script>

<style>
	main {
		background-color: #f5f5f5 !important;
	}
</style>

<svelte:head>

</svelte:head>

<Nav {segment}/>

<main>
	<slot></slot>
</main>

<Footer/>