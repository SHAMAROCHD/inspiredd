<!-- saved from url=(0069)file:///C:/Users/CHAMA/OneDrive/Desktop/Nouveau%20dossier/PROJET.html -->
<html><head><meta http-equiv="Content-Type" content="text/html; charset=UTF-8"></head><body><header>
	<link rel="stylesheet" href="css.css">
    <link rel="stylesheet"  href="projet inspired.html">

	<style type="text/css">

         		{
			text-decoration: none;
		}
		.navbar{
			background: #f2f3f4   ;font-family: Times, Times New Roman; padding-right: 15px; padding-left: 15px;
            
		}
		.navdiv{
			display: flex; align-items: center; justify-content: space-between;
		}
		.logo{
			align-self: center;
		}
		button{
			background-color:#674a44 ;margin-left: 8px ;border-radius: 8px; padding: 8px; width: 70px;
		}
        
        button a{
        	color: white; font-weight: bold; font-size: 10px;
        }
        .title {
            flex-grow: 1;
            text-align: center;
            font-size: 24px; /* Change font size as needed */
            font-weight: bold;
        }

	</style>

</header>


</body>


<body>
 

<nav class="navbar">
	<div class="navdiv">
	<div class="logo"><img src="LOGO.png" width="50" height="40">	

</div>
<div class="title"><h1>inspirED</h1></div>
<ul>
		<button><a href="PROJET.html">Accueil</a></button>
		<button><a href="projet inspired.html">Compte</a></button>


</nav>

<style>
        
        .dialog {
            display: none; 
            position: fixed;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
            background-color: #fff;
            border: 1px solid #ccc;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
            padding: 20px;
            z-index: 1000;
        }
        .overlay {
            display: none; 
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background-color: rgba(0, 0, 0, 0.5);
            z-index: 999;
        }
        .button {
            padding: 10px 15px;
            background-color: #674a44;
            color: white;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
        .button:hover {
            background-color: #7f8c8d;
            
        }
    </style>
</head>
<body>

    <div class="overlay" id="overlay"></div>
    <div class="dialog" id="dialog">
        <h2>Bienvenue !</h2>
        <p>Vous êtes sur le point de créer un compte. Cliquez sur le bouton ci-dessous pour continuer.</p>
        <button class="button" onclick="goToRegistration()">Créer</button>
        <button class="button" onclick="closeDialog()">Annuler</button>
    </div>

    <script>
        // Afficher la barre de dialogue au chargement de la page
        window.onload = function() {
            document.getElementById('overlay').style.display = 'block';
            document.getElementById('dialog').style.display = 'block';
        };

        // Rediriger vers la page de création de compte
        function goToRegistration() {
            window.location.href = "projet inspired.html"; // Remplacez par l'URL de votre page de création de compte
        }

        // Fermer la barre de dialogue
        function closeDialog() {
            document.getElementById('overlay').style.display = 'none';
            document.getElementById('dialog').style.display = 'none';
        }
    </script>

</body>

<body>
    <h1>Bienvenue sur notre plateforme</h1>
    <div class="container">
        <div class="card">
            <img src="1.jpg" alt="Description de l'image" class="card-img">
            <div class="text">
                <h3>Notre site web:</h3>
                <p><i>Notre site est une plateforme éducative, communautaire et collaborative qui vise à faciliter l’accès aux informations et aux cours pour les étudiants de tous les établissements spécialisés en génie énergétique, génie thermique, efficacité énergétique, et développement durable. De plus, notre site a pour objectif de garantir un environnement optimal pour l'étude en proposant des playlists musicales et en intégrant la gestion du temps grâce à la méthode Pomodoro. 
                    Notre site proposera également des suggestions de stages pour ces spécialités, des exemples de rapports de stage, ainsi que le partage de nos expériences de stage. En plus, nous souhaitons offrir un espace de communication pour permettre aux utilisateurs d’échanger des questions et des conseils.

             Nous prévoyons également de collaborer avec des professeurs pour proposer des cours supplémentaires, individuels ou en groupe, payants selon leur disponibilité. Un espace personnel sera créé pour chaque personne inscrite et connectée au site, afin de rendre l'expérience utilisateur plus personnalisée.</i></p>
</p>
               
            </div>
        </div>
        <div class="card">
            <img src="2.jpg" alt="Description de l'image" class="card-img" >
            <div class="text">
                <h3>Une Réponse à la rareté des ressources éducatives</h3>
                <p><i>Ce site a été créé pour répondre à un besoin important : la rareté des cours et des ressources pédagogiques dans les domaines du génie énergétique, du génie thermique et de l’efficacité énergétique.

                 Nous avons constaté que peu de plateformes offrent des contenus accessibles et adaptés aux étudiants de ces filières, ce qui complique l’apprentissage. Notre objectif est de combler cette lacune en proposant un espace où chacun peut trouver des cours complets, des ressources pratiques et des outils d’accompagnement pour réussir dans ces disciplines essentielles pour l’avenir.</p></i>
                
            </div>
        </div>
           <div class="card">
            <img src="3.jpg" alt="Description de l'image" class="card-img">
            <div class="text">
                <h3>Une Plateforme Évolutive et Participative</h3>
                <p><i> Ce site est le fruit du travail collectif d'un groupe d'étudiants passionnés, issus des domaines de l'énergie et du développement durable. Conscients des défis auxquels les étudiants font face pour accéder à des ressources pédagogiques de qualité, nous avons conçu cette plateforme pour évoluer et s'enrichir grâce à la participation active de chacun.

                Chaque membre a la possibilité de publier des cours, de partager des ressources pédagogiques et de poser des questions à la communauté. Nous croyons fermement que l'échange de connaissances est essentiel pour progresser ensemble. En contribuant à la plateforme, chaque utilisateur participe à la création d'une base de données de plus en plus complète, tout en favorisant un environnement d'entraide et de collaboration.</p></i>
               
            </div>
        </div>

<div class="card">
 	
           <div class="container">
            <div class="text">
            	<h3>Modules de filière </h3>
               
<p><i>L'un des objectifs de notre site est de guider les étudiants en leur offrant une vision claire de leur domaine d'étude et de leur parcours scolaire. En effet, de nombreux étudiants dans le secteur énergétique rencontrent des difficultés en matière d'orientation et d'accès aux ressources pédagogiques et aux informations pertinentes.<br>
Cliquez ci-contre!</i></p>

            </div>
        </a></div></div>


 <div class="card">
 	<a href="Page4.html" class="carte">
            <img src="bO.png" alt="Description de l'image" class="card-img">
            <div class="text">
                <h3>Be inspirED</h3>

            </div>
        </a></div>


  <div class="card">
 	<a href="page2.html" class="carte">
            <img src="mec.jpg" alt="Description de l'image" class="card-img">
            <div class="text">
                <h3>Mécanique</h3>
            </div>
        </a></div>

  <div class="card">
 	<a href="page1.html" class="carte">
            <img src="ent.jpg" alt="Description de l'image" class="card-img">
            <div class="text">
                <h3> Tec, Droit et Entrepreunariat</h3>
            </div>
        </a></div>

<div class="card">
 	<a href="Page3.html" class="carte">
            <img src="IM.jpg" alt="Description de l'image" class="card-img">
            <div class="text">
                <h3> Energies renouvelables</h3>
            </div>
        </a></div>

<div class="card">
 	<a href="page 5.html" class="carte">
            <img src="ST.jpg" alt="Description de l'image" class="card-img">
            <div class="text">
                <h3> TPs PFE et Stages</h3>
            </div>
        </a></div>


<div class="card">
 	<a href="page6.html" class="carte">
            <img src="Courants_de_convection.png" alt="Description de l'image" class="card-img">
            <div class="text">
                <h3>Transfert de chaleur et de masse</h3>
            </div>
        </a></div>

<div class="card">
 	<a href="page7.html" class="carte">
            <img src="ther.jpg" alt="Description de l'image" class="card-img">
            <div class="text">
                <h3>Thermodynamique</h3>
            </div>
        </a></div>
</p></div></div></p></div></div></div></body>

<footer class="footer">
    <div class="footer-content">
        <h3>Contactez-nous</h3>
        <p>
            Adresse :  Agadir, Maroc<br>
            Téléphone : 0611647707<br>
            Email : <a href="mailto:chamarochd0@gmail.com">Contactez-nous</a>
        </p>
        <ul class="footer-links">
            <li><a href="PROJET.html">Accueil</a></li>
            <li><a href="page1.html">Tec, Droit et Entrepreunariat</a></li>
            <li><a href="Page3.html">Energies renouvelables</a></li>
            <li><a href="Page4.html">Be InspirED!</a></li>
            <li><a href="page2.html">Mécanique</a></li>
            <li><a href="page6.html">Transfert de chaleur et de masse</a></li>
            <li><a href="page7.html">Thermodynamique</a></li>
             <li><a href="page 5.html">TPs PFE et Stages</a></li>
         <li>


    </ul>
</nav>


        </ul>
    </div>
</footer>
