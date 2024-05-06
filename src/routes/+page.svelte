<script>
	import main_logo from "$lib/images/logo.min.svg";
</script>

<svelte:head>
	<title>Home</title>
	<meta name="description" content="Svelte demo app" />
</svelte:head>

<section>
	<h1>
		<span class="welcome">
			<picture>
				<img src={main_logo} alt="LOGO" />
			</picture>
		</span>

		<p>
			A Meta-Language for LLMs to <br />Generate Structured Information
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
		padding: 0 0 calc(100% * 495 / 2048) 0;
	}

	.welcome img {
		position: absolute;
		width: 100%;
		height: 100%;
		top: 0;
		display: block;
	}
</style>
