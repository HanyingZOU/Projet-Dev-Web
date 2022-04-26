<script context="module">
	export const prerender = true;
</script>

<script>
	import Counter from '$lib/Counter.svelte';
</script>

<svelte:head>
	<title>Accueil</title>
	<meta name="description" content="Svelte demo app" />
</svelte:head>

<section>
	<h1>
		<div>
			Bonjour! &nbsp Bienvenue à 
		</div>
		<div class="orange">EaStudy</div>
	</h1>

	<h1>
			Souhaitez-vous:
	</h1>
	<div class="box">
		<div class="left">
			<div>
				<img src="https://cdn-icons-png.flaticon.com/512/1089/1089129.png" width = "200px" class="img-circle" >
			</div>
				<h1></h1>
			<a href="/connextion" class="bouton">Donner des cours 
		</div>
		<div class="right">
			<img src="https://p7.hiclipart.com/preview/592/386/548/student-education-study-skills-learning-computer-icons-streamers.jpg" width = "200px" class="img-circle" >
			<h1></h1>
			<a herf="#" class="bouton" > Prendre des cours </a>
		</div>
		
	</div>
</section>

<style>
	section {
		display: flex;
		flex-direction: column;
		justify-content: center;
		align-items: center;
		flex: 1;
		text-align: center;
	}

	h1 {
		width: 100%;
	}

	.bouton{
    background-color:#6B72E1;
    color: white;
    padding: 10px 15px;
    border-radius: 3px;
	}

	.img-circle{
		border-radius: 50%
	}

	body{
    margin:0;
  }
	.box{
		width:80%;
		margin:0 auto;
		overflow:hidden;
	}
	.box .left{
		width:50%;
		height:400px;
		float:left;
	}
	.box .right{
		width:50%;
		height:400px;
		float:left;
	}
	.orange{
		color:orange;
		font-style: italic;
	}
</style>
