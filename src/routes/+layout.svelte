<script lang="ts">
	import '../app.css';
	let { children } = $props();
</script>

<title>hakobox!</title>

<nav class="text-lg">
	<a href="/">Home</a>
	<a href="/projects">Projects</a>
	<a href="/about">About</a>
</nav>

{@render children()}
