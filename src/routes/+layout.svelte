<header>
	<div>
		<a href="/">Home</a>
		<a href="/søknad">Søknad</a>
	</div>
	<div>
		<button type="button">Dropdown med logut TODO</button>
	</div>
</header>

<slot />

<style>
	header {
		display: flex;
		justify-content: space-between;
		gap: 1rem;
		padding: 1rem;
		background-color: #a86400;
	}

	a {
		text-decoration: none;
		color: black;
	}
</style>
