<svelte:head>
	<link rel="stylesheet" href="/main.css" />
	<meta
		name="description"
		content="Dan Norris, the endorsed democratic candidate for Cheltenham's Ward 5."
	/>
	<meta property="og:type" content="website" />
	<meta property="og:image" content="https://norrisforcheltenham.com/img/dan.jpg" />
	<meta
		property="og:description"
		content="Dan Norris, the endorsed democratic candidate for Cheltenham's Ward 5."
	/>
</svelte:head>

<div id="header">
	<h1 id="logo">Dan Norris</h1>
	<h2 id="tagline">
		Our <em>choice</em> our <em>voice</em> <span class="keepTogether">for Ward 5</span>!
	</h2>
</div>

<div id="content">
	<slot />
</div>

<div id="footer">
	<p>Paid for by Committee to Elect Dan Norris Commissioner</p>
</div>

<style>
	h1,
	h2 {
		margin: 0px;
	}
	#header {
		text-align: center;
		background: #243e6d;
		color: #8ee4fc;
		padding: 5px;
		margin-bottom: 20px;
		padding-top: 20px;
	}
	#logo {
		font-size: 4em;
	}
	#tagline {
		text-transform: uppercase;
		margin: 10px;
	}
	#content {
		max-width: 600px;
		margin: auto;
	}
	#footer {
		text-align: center;
		margin-top: 40px;
		font-size: 0.8em;
	}
</style>
