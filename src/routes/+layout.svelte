<script lang="ts">
	import '../app.scss';
	let { children } = $props();
</script>

<title>hakobox!</title>

<a href="/">
	<img src="/logo.png" alt="Home" />
</a>

<nav class="text-lg">
	<a href="/projects">Projects</a>
	<a href="/about">About</a>
</nav>

{@render children()}

<footer>
	<p>&copy; Zane Little-James and Sato Koyama, 2025</p>
	<!--
		<a href="mailto:contact@hakobox.xyz">
			<img class="footer-img" src="img/mail.svg" alt="mail icon" />
		</a>
		<a href="http://www.twitter.com">
			<img src="img/twitter.svg" alt="twitter icon" />
		</a>
		<a href="http://www.youtube.com">
			<img src="img/youtube.svg" alt="youtube icon" />
		</a>
	-->
</footer>
