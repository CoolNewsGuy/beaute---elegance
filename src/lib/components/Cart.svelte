<script lang="ts">
	import product1 from '$lib/assets/Sample Imgs/Products Imgs/photo_11.jpg';
</script>

<img src={product1} alt="product1" />
<div class="Description" style="display: inline-block;vertical-align: top;">
	<h3>BOURJOIS</h3>
	<h4>Fond de teint 123 30ml - bourjois -</h4>
	<h4 style="margin-left: 5px;">950.00 DZD</h4>
	<p>Choisissez Votre teint</p>
	<div class="colors">
		<button class="CB" style="background-color: rgb(255,219,172)">51</button>
		<button class="CB" style="background-color: rgb(241,194,125)">52</button>
		<button class="CB" style="background-color: rgb(224,172,105)">53</button>
		<button class="CB" style="background-color: rgb(198,134,66)">54</button>
		<button class="CB" style="background-color: rgb(168,109,57)">55</button>
		<p>Quantité</p>
		<div class="Counter">
			<span class="minus">-</span>
			<span class="numb">1</span>
			<span class="plus">+</span>
		</div>
		<button class="buynow">Acheter maintenent</button>
	</div>
</div>

<style>
	h3 {
		font-family: arial;
		color: rgb(173, 172, 172);
	}
	h4 {
		font-weight: lighter;
		font-family: arial;
	}
	p {
		font-family: Arial;
		font-size: small;
	}
	.CB {
		width: 30px;
		height: 30px;
		border: none;
		color: white;
		border-radius: 100px;
		margin-right: 8px;
		margin-bottom: 10px;
		cursor: pointer;
	}
	.colors {
		width: 200px;
	}
	.Counter {
		border-style: solid;
		border-color: black;
		padding: 5px;
		padding-right: 5px;
		padding-left: 5px;
		display: inline-block;
		border-width: 1px;
	}
	.minus {
		margin-right: 15px;
		cursor: pointer;
	}
	.plus {
		margin-left: 15px;
		cursor: pointer;
	}
	.buynow {
		margin-top: 14px;
		margin-bottom: 14px;
		margin-left: 2px;
		margin-right: 2px;
		padding-top: 14px;
		padding-bottom: 14px;
		padding-right: 30px;
		padding-left: 30px;
		border: solid transparent;
		border-width: 1.5px;
		background-color: rgb(241, 193, 201);
		border-radius: 6px;
		cursor: pointer;
		transition: 0.15s;
	}
	.buynow:hover {
		color: rgb(238, 112, 133);
		border-color: rgb(238, 112, 133);
		background-color: white;
	}
</style>
