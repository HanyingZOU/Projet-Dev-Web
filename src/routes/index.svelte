

<body>

	<nav>
		<a class="boutonmobile" href="javascript: bascule_affichage('menu');">&#x2630;</a>
		<ul id="menu">
			<li><a href="#"> Accueil</a></li>
			<li><a href="#Inscription"> Inscription</a></li>
			<li><a href="#"> Nos forces</a></li>
			<li><a href="#"> Nos tuteurs</a></li>

	</nav>

	<header>

		<h1>
			<div>
				Bonjour! &nbsp Bienvenue à 
			</div>
			<div class="orange">EaStudy</div>
		</h1>

	</header>
	<main class = "main">
		<section id="Inscription">
			<div class="soustitre">
				<h2>Inscription</h2>
			</div>
			<h1>Souhaitez-vous:</h1>
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

		<section id="Nos forces" class="grid-wrap">
			<div class="soustitre">
				<h2>Nos forces</h2>
			</div>
			
    	<div class="force force1">
        <h3>Soustitre</h3>
        <p>Annonce</p>
    	</div>
    	<div class="force force2">
        <h3>Soustitre</h3>
        <p>Annonce</p>
   		</div>
    	<div class="force force3">
        <h3>Soustitre</h3>
        <p>Annonce</p>
    	</div>
    	<div class="force force4">
        <h3>Soustitre</h3>
        <p>Annonce</p>
    	</div>

		</section>	

		<section id="equipe " class="grid-wrap grid-gt">

			<div class="soustitre">
      	<h2>Nos tuteurs</h2>
    	</div>

			<div class="coloum">

				<div class="gauche">
					<div class="equipe ">
						<img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQ1_0jWTzJP1Dr6Msi1jngknM9Akh_N0dS9HA&usqp=CAU" class="img">
						<div>
							<h3>Prenom Nom</h3>
							<h4>Promo xxxx</h4>
							<p>Presentation</p>
							<p class="equipecontact"><a href="#contact">Contact</a></p>
						</div>
					</div>
				</div>

				<div class="middle">
					<div class="equipe">
						<img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQ1_0jWTzJP1Dr6Msi1jngknM9Akh_N0dS9HA&usqp=CAU" class="img">
						<div>
							<h3>Prenom Nom</h3>
							<h4>Promo xxxx</h4>
							<p>Presentation</p>
							<p class="equipecontact"><a href="#contact">Contact</a></p>
						</div>
					</div>
				</div>

				<div class="droite">
					<div class="equipe">
						<img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQ1_0jWTzJP1Dr6Msi1jngknM9Akh_N0dS9HA&usqp=CAU" class="img">
						<div class="equipetexte">
							<h3>Prenom Nom</h3>
							<h4>Promo xxxx</h4>
							<p>Presentation.</p>
							<p class="equipecontact"><a href="#contact">Contact</a></p>
						</div>
					</div>
				</div>

			</div>

  </section>


	</main>

</body>

<section>


</section>

<style>

	
	* { 
		padding: 0; 
		box-sizing: border-box; 
	}
	body, a { 
		font-family: Arial, 
		sans-serif; 
		color: darkslategray; 
	}

	section {
		display: flex;
		flex-direction: column;
		justify-content: center;
		align-items: center;
		flex: 1;
		text-align: center;
	}
	nav ul{
		display: flex;
		list-style-type: none;
		padding:0px 0px 0px 0px;
		margin-top:0px;
	}

	nav li{
		flex: 1 1 auto;
	}


	nav a{
		display: block;
		background-color: #bec7d4; 
		line-height: 60px; 
		text-align: center; 
		font-size: 25px; 
		text-decoration: none; 
		color:#2d3a7a;
	}
	nav a:hover { 
		background-color: #969bb3; 
	}

	h1 {
		width: 100%;
	}

	h2 { 
		display: inline-block; 
		margin: 20px 0 20px 0; 
		border-bottom: solid 6px dimgray; 
		font-size: 1.8rem; 
		font-weight: normal; 
	}
	.img{
		width: 150px;
		height: 150px;
		border-radius: 50%
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

	.soustitre{
		margin: 10px;
		width: 100%;
		height:50px 0 30px 0;
    text-align: center;
		background-color: #d3dbe6;
	}

	body{
    margin:0;
  }
	.box{
		width:90%;
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
	.boutonmobile { 
		display: none; 
	}

	.force { 
		padding: 15px 15px; 
		width :90%;
	}
	.force1 { 
		background-color: #e0e0e0; 
	}
	.force2 { 
		background-color: #c0c0c0; 
	}
	.force3 { 
		background-color: #989898; color: #FFFFFF; 
	}
	.force4 { 
		background-color: #707070; color: #FFFFFF;
	}

  .cloum{
		width:90%;
		margin:0 auto;
		overflow:hidde
	}
	.coloum .gauche{
		width:33%;
		height:400px;
		float:left;
	}
	.coloum .middle{
		width:33%;
		height:400px;
		float:left;
	}
	.coloum .droite{
		width:33%;
		height:400px;
		float:left;
	}

	.equipe { 
		position: relative; 
		padding-bottom: 70px; 
		border: solid 1px #e0e0e0;
		width: 95%;
		height: 100%;
	}
	.equipe:hover { 
		box-shadow: 3px 3px 10px lightgray ; 
	}
	.equipetexte { 
		padding: 2% 2% 2% 2%; 
	}
	.equipe h3 { 
		margin: 0; 
		padding-top: 5px; 
		font-size: 1.8rem; 
	}
	.equipe h4 { 
		font-size: 1.3rem; 
		font-weight: normal; 
		color: #909090; 
	}
	.equipe p {  
		font-size: 1.1rem; 
	}
	.equipecontact { 
		margin: 0; 
		text-align: center;
	}
	.equipecontact a { 
		display: block; 
		width: 95%; 
		padding: 20px; 
		position: absolute; 
		left: 2.5%; 
		bottom: 2.5%; 
		background-color: #e0e0e0; 
		font-size: 1.3 rem;
		text-decoration: none;
	}
	.equipecontact a:hover { 
		background-color:  #c0c0c0m
	}


	
	@media only screen and (max-width: 479px) {
		.visible { 
			display: block; 
		}
		.boutonmobile { 
			display: block; 
			text-align: right; 
			padding-right: 10%; 
			border: solid 1px #c0c0c0; 
		}
		nav ul { display: none; margin: 0; }
		nav li { border: solid 1px #c0c0c0; }
		nav li a { text-align: left; padding: 0 10%; }
		footer { margin-top: 150px; }
	}



</style>
