<script>
	import '../app.css';
	import Hamburger from '../components/hamburger.svelte';
</script>

<div class="nav-bar">
	<Hamburger />
	<p>Chapman Haus Works</p>
</div>
<slot />

<style>
	.nav-bar {
		position: sticky;
		top: 0;
		height: 3rem;
		width: 100%;
		display: flex;
		gap: 1rem;
		align-items: center;
		box-shadow: 0px 1px 6px #313131;
		padding: 0px 1rem;
	}
</style>
