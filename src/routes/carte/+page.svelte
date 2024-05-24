<script lang="ts">
    import HeaderTopContainer from '$lib/components/HeaderTopContainer.svelte';
    import Emptycarte from '$lib/components/Emptycarte.svelte';
    
    import FeaturesContainer from '$lib/components/FeaturesContainer.svelte';
    import InfoContainer from '$lib/components/InfoContainer.svelte';
    import logo from '$lib/assets/logo.png';
</script>

<link rel="shortcut icon" href={logo} type="image/x-icon" />
<svelte:head>
	<link rel="preconnect" href="https://fonts.googleapis.com" />
	<link rel="preconnect" href="https://fonts.gstatic.com" />
	<link href="https://fonts.googleapis.com/css2?family=Open+Sans&display=swap" rel="stylesheet" />
	<link
		href="https://fonts.googleapis.com/css2?family=Abril+Fatface&display=swap"
		rel="stylesheet"
	/>
	<link
		href="https://fonts.googleapis.com/css2?family=Andada+Pro:ital@0;1&display=swap"
		rel="stylesheet"
	/>

</svelte:head>
<header>
    <Emptycarte />
</header>

<footer>
	<h2 class="footer-title">A propose de nous</h2>
	<div class="container">
		<InfoContainer />
		<FeaturesContainer />
	</div>
	<div class="copyright-container">&copy; 2024 Beaute & Elegance. All rights reserved.</div>
</footer>

<style>
  footer {
		margin-top: 15rem;
	}

    header {
        font-family: 'Open Sans', sans-serif;
        padding-top:16.4rem;


    }
	.footer-title {
		font-family: 'Abril Fatface';
		font-weight: lighter;
		text-align: center;
	}
	footer .container {
		display: flex;
		margin-top: 5rem;
		align-items: start;
		justify-content: space-evenly;
		gap: 4rem;
		flex-wrap: wrap;
		padding-inline: 3rem;
	}
	.copyright-container {
		margin-top: 8rem;
		min-height: 5rem;
		background: #f0d9d9;
		display: grid;
		place-content: center;
	}
</style>
