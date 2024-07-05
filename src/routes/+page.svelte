<script lang="ts">
	import Comic from './Comic/+page.svelte';
	import Contact from './Contact/+page.svelte';
	import Content from './Content/+page.svelte';
	import Header from './Header/+page.svelte';
</script>

<Content />

<style>
	:root {
		font-family: Inter, system-ui, Avenir, Helvetica, Arial, sans-serif;
		line-height: 1.5;
		font-weight: 400;

		font-family: 'Poppins', sans-serif;
		font-weight: 400;
		color: white;
		background: rgb(0, 0, 0);
		background: linear-gradient(90deg, rgba(0, 0, 0, 1) 0%, rgba(26, 14, 1, 1) 100%);

		font-synthesis: none;
		text-rendering: optimizeLegibility;
		-webkit-font-smoothing: antialiased;
		-moz-osx-font-smoothing: grayscale;
	}
</style>
