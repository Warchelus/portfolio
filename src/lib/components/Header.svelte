<script>
	import { page } from '$app/stores';
	import Nav from '$lib/components/Nav.svelte';
</script>

<header>
	<img src="/logo.png" alt="">
	<Nav />
</header>

<style>
	header {
		display: flex;
		padding: 10px 30px;
		background-color: white;
		justify-content: space-between;
		align-items: center;

	}

	img{
		height: 75px;
	}
</style>
