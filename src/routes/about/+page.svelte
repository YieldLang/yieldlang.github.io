<svelte:head>
	<title>About YieldLang</title>
	<meta name="description" content="About this app" />
</svelte:head>

<div class="text-column">
	<h1>
		About the <code>YieldLang</code>
	</h1>

	<p>
		<code>YieldLang</code> is a
		<a href="https://en.wikipedia.org/wiki/Metalanguage" target="_blank"
			>meta-language</a
		> for generating structured text (ST) for large language models (LLMs) or
		guide LLMs to generate ST. Currently provided as a Python package.
	</p>
	<p>
		To install the <code>YieldLang</code>, use the following command in your
		terminal:
	</p>

	<pre style="user-select: all;"><code
			style="margin-right: 0.5em; user-select: none;">$</code
		><span class="pip">pip</span> <span class="install">install</span
		> yieldlang</pre>
	<ul>
		<li>Based on a coroutine generator and sampler architecture</li>
		<li>
			Stream-sends characters and parses the context above into a syntax
			tree
		</li>
		<li>Build formal grammars with classes, methods, and combinators</li>
	</ul>
	<p>
		More information on the GitHub home page: <a
			href="https://github.com/YieldLang"
			target="_blank"><b>github.com/YieldLang</b></a
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
