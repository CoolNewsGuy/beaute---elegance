<script lang="ts">
    import HeaderTopContainer from '$lib/components/HeaderTopContainer.svelte';
    import Emptycarte from '$lib/components/Emptycarte.svelte';
    import Navbar from '$lib/components/Navbar.svelte';
    import FeaturesContainer from '$lib/components/FeaturesContainer.svelte';
    import InfoContainer from '$lib/components/InfoContainer.svelte';
</script>
<div class="fixed">
    <HeaderTopContainer />
    <Navbar />
</div>
<slot/>

    <style>
        .fixed {
		position: fixed;
		z-index: 9;
		width: 100%;
		box-shadow: 0 0 3rem #0002;
	}
    </style>