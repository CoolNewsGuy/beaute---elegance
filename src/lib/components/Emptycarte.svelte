<script lang="ts">
	import Panier from '$lib/assets/icons/BE Panier.png';
</script>

<section class="TitlePanier">Panier</section>
<div class="Empty">
	<img style="width: 20vh;, height: 20vh;" src={Panier} alt="Panier" />
	<p style="font-size: 2.3rem;">Votre panier est vide!</p>
	<p>Parcourez nos catégories et découvrez nos meilleures offres!</p>
	<button>Retour à la boutique</button>
</div>


<style>
	:global(*) {
		margin: 0;
		padding: 0;
		box-sizing: border-box;
		font-family: 'Open Sans', sans-serif;
		scroll-behavior: smooth;
	}

	.TitlePanier {
		text-align: center;
		color: #eec8c8;
		align-items: center;
		padding-block: 1rem;
		font-size: 2.5rem;
		background: white;
		border: 3px solid #f0d9d9;
	}
	.Empty {
		align-items: center;
		display: block;
		text-align: center;
		margin-top: 6rem;
	}
	.Empty p {
		padding: 0.8rem;
	}
	.Empty button {
		background: #f0d9d9;
		padding: 0.7rem 5.5rem 0.7rem 5.5rem;
		font-size: 1.8rem;
		font-weight: 550;
		margin-top: 2rem;
		border: none;
	}
</style>
