<script>
	import '../tailwind.css'
	import Nav from './Nav.svelte'
</script>

<Nav />

<slot></slot>

<style>
	@tailwind base;
	@tailwind components;
</style>
