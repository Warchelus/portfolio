<script>
	import Hero from '../lib/components/Hero.svelte';
</script>

<svelte:head>
	<title>Home</title>
	<meta name="description" content="Svelte demo app" />
</svelte:head>

<section>
	<Hero title="Wesner's Portfolio" />
</section>
<section>
	<h2>About Me</h2>
	<p>
		I am a 37 year old running coach residing in Massachusetts. I have been running for 25 years and
		have been coaching for 10 years. I have a passion for running and helping others achieve their
		goals. I have coached runners of all levels from beginners to elite athletes. I have a degree in
		exercise science and have completed the RRCA coaching certification. I have also completed the
		USATF level 1 coaching certification. I have a passion for helping others achieve their goals
		and I am excited to help you achieve yours. I look forward to working with you and helping you
		achieve your goals.
	</p>
</section>
<section>
	<h2>My Work</h2>
	<!-- 3 cards links to other pages -->
	<div class="work-examples">
		<a href="/sales">
			<div class="card">
				<h1>Sales Page</h1>
				<p>Learn more about my running coaching services.</p>
			</div>
		</a>
		<a href="/form">
			<div class="card">
				<h1>Sign up</h1>
				<p>Start your running journey today!</p>
			</div>
		</a>
		<a href="/tribute">
			<div class="card">
				<h1>Blog</h1>
				<p>Read my blog</p>
			</div>
		</a>
	</div>
</section>

<style>
	section {
		display: flex;
		flex-direction: column;
		justify-content: center;
		align-items: center;
		flex: 0.6;
	}

	.work-examples {
		display: flex;
		flex-direction: row;
		align-items: center;
		gap: 3rem;
	}

	.card {
		display: flex;
		flex-direction: column;
		justify-content: center;
		align-items: center;
		background-color: #f0f0f0;
		padding: 2rem;
		border-radius: 1rem;
		box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
		transition: transform 0.2s;
	}

	h2 {
		font-size: 4rem;
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
