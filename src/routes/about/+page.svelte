<svelte:head>
	<title>About</title>
	<meta name="description" content="About this app" />
</svelte:head>

<div class="text-column">
	<h1>
		About the <code>YieldLang</code>
	</h1>

	<p>
		<b>Work in progress now.</b>
	</p>
	<p>
		You can install the YieldLang by typing the following into your command
		line and following the prompts:
	</p>

	<pre><span class="pip">pip</span> <span class="install">install</span
		> yieldlang</pre>
	<p>
		More information on the GitHub home page: <a
			href="https://github.com/YieldLang"
			target="_blank">github.com/YieldLang</a
		>
	</p>
</div>

<style>
	span.pip {
		color: var(--color-theme-1);
	}
	span.install {
		color: var(--color-theme-2);
	}
</style>
