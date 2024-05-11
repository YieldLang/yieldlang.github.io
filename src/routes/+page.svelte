<script>
	import main_logo from "$lib/images/logo.min.svg";
</script>

<svelte:head>
	<title
		>YieldLang - A meta-Language for LLMs to process structured info</title
	>
	<meta
		name="description"
		content="A meta-Language for LLMs to process structured info."
	/>
</svelte:head>

<section>
	<h1>
		<span class="welcome">
			<picture class="hero">
				<img src={main_logo} alt="LOGO" draggable="false" />
			</picture>
		</span>
		<div style="width: 61.8%; margin: 0">
			<p>A Meta-Language for LLMs to Process Structured Info</p>
		</div>
	</h1>

	<a
		href="https://github.com/YieldLang"
		target="_blank"
		style="margin-top: -2.5em"
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
		display: contents;
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

	.hero img {
		transition: all 0.3s ease;
	}

	.hero img:hover {
		transform: scale(1.2);
		transition: all 0.3s ease;
	}
</style>
