<script>
	import main_logo from "$lib/images/logo.min.svg";
</script>

<svelte:head>
	<title
		>YieldLang - A meta-Language for LLMs to produce or parse structured info</title
	>
	<meta
		name="description"
		content="A meta-Language for LLMs to produce or parse structured info."
	/>
</svelte:head>

<section>
	<h1>
		<span class="welcome">
			<picture class="hero">
				<img src={main_logo} alt="LOGO" draggable="false" />
			</picture>
		</span>

		<p>
			A Meta-Language for LLMs to <br />Produce or Parse Structured Info
		</p>
	</h1>

	<a href="https://github.com/YieldLang" target="_blank"
		><h2 style="font-size: 1.414em"><b>github.com/YieldLang</b></h2></a
	>
</section>

<style>
	section {
		display: flex;
		flex-direction: column;
		justify-content: center;
		align-items: center;
		flex: 0.6;
	}

	h1 {
		width: 100%;
	}

	.welcome {
		display: block;
		position: relative;
		width: 100%;
		height: 0;
		padding: 0 0 calc(100% * 0.618 * 0.382) 0;
		user-select: none;
	}

	.welcome img {
		position: absolute;
		width: 100%;
		height: 100%;
		top: 0;
		display: block;
	}

	.hero {
		padding-top: 3.5rem;
	}

	.hero img {
		transition: all 0.3s ease;
	}

	.hero img:hover {
		transform: scale(1.1, 1.1);
		transition: all 0.3s ease;
	}
</style>
