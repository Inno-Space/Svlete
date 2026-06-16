<script>
	let { children } = $props();
</script>
<nav>
	<a href="/">Home</a>
	<a href="/about">紹介</a>
</nav>

<hr />
{#if children}
	{@render children()}
{/if}
<hr />

<h1>LAYOUT</h1>

<footer>
	2026年Svelte練習ページ作成する。All right reserved
</footer>

<style>
	nav {
		padding: 1rem;
		background-color: #f4f4f4;
	}

	nav a {
		margin-right: 10px;
		text-decoration: none;
		font-weight: bold;
		color: #ff3e00;
	}

	footer {
		text-align: center;
		font-size: 0.8rem;
		color: gray;
	}
</style>