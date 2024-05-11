<script lang="ts">
	import { concurrent } from "svelte-typewriter";
</script>

<svelte:head>
	<title>About YieldLang</title>
	<meta name="description" content="About this app" />
</svelte:head>

<div class="text-column">
	<h1 use:concurrent={{ interval: 60 }} style="min-height: 1.5em">
		<span>About the</span> <code>YieldLang</code>
	</h1>

	<p>
		<code>YieldLang</code> is a
		<a href="https://en.wikipedia.org/wiki/Metalanguage" target="_blank"
			>meta-language</a
		>
		for generating structured text (ST) for large language models (LLMs) or guide
		LLMs to generate ST. Currently provided as a
		<a href="https://pypi.org/project/yieldlang/" target="_blank"
			>Python package</a
		>.
	</p>
	<p>
		To install the <code>YieldLang</code>, use the following command in your
		terminal:
	</p>

	<pre
		style="user-select: all; white-space: break-spaces; min-height: 1em"
		use:concurrent={{ interval: 60 }}><code
			style="margin-right: 0.5em; user-select: none;">$</code
		><span class="pip">pip</span> <span class="install">install</span> <span
			>yieldlang</span
		></pre>
	<ul use:concurrent={{ interval: 7 }} style="min-height: 1em">
		<li>🧠 Based on a coroutine generator and sampler architecture</li>
		<li>
			🤖 Stream-sends characters and parses the context above into a
			syntax tree
		</li>
		<li>🦾 Build formal grammars with classes, methods, and combinators</li>
	</ul>
	<p use:concurrent={{ interval: 15 }} style="min-height: 1em">
		<span>More information on the GitHub home page:</span>
		<a href="https://github.com/YieldLang" target="_blank"
			><b>github.com/YieldLang</b></a
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
