# html-css-Excercice
<!DOCTYPE html>
<html>
<!-- Head = métadonnées, informations sur la page uniquement visibles par le navigateur(non-affichées) -->
	<head> 
		<meta charset="utf-8" /> <!-- set de caractères(ce qui gère les symboles, accents etc propres aux langues) utilisé (ici utf-8) -->
		<link rel="stylesheet" href="feuille_css.css" /> <!-- rel = type de fichier vers lequel le link est fait, href = adresse du fichier, ici la feuille de style css (stylesheet) -->
		<link href='https://fonts.googleapis.com/css?family=Lobster' rel='stylesheet' type='text/css'> <!-- Ici lien vers les fonts google -->
		<title>Page d'exo</title> <!-- Titre de la page (ce qui s'affiche en haut du navigateur ou dans l'onglet) -->
	</head>
<!-- Body = Corps de la page (tout ce qui s'affiche dans le navigateur) -->
	<body>
		<!-- header :balise permettant de d'élimiter ce qui sera en en-tête de page -->
		<header>
			<img src="http://www.images-libres.net/wp-content/uploads/2013/02/photo-libre-de-droit-de-hibou-www.images-libres.net_.jpg" /><br> <!-- src = où se trouve l'image -->
			</br><h2>Un joli et gros titre</h2>
			<p><u>Un paragraphe</u></p>
			<!-- nav = balise délimitant un menu de navigation -->
			<nav>
				<!-- ul = liste non ordonnées (des petits points), ol = liste ordonnées (des chiffres) -->
				<ul id="menu_bin"> <!-- On a ajouté un id à ul, l'id est un identifiant unique (il ne peut y avoir qu'un seul id="menu_bin" sur la page !), il permet de sélectionner en css cet élement précis -->
					<li><a href="page_flo.html" >Page de Floriane</a></li> <!-- li= un élement de la liste, a = un lien avec un href qui pointe sur l'adresse du lien -->
					<li><a href="page_bin.html" >Page de Biniam</a></li>
				</ul>
			</nav>
		</header>
		<!-- section est une balise permettant de délimiter des blocs de contenu dans la page -->
		<section>
			<p id="para">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Assumenda officiis reprehenderit, quae minus, autem, dolorem facere deserunt sunt, libero a molestias nobis maiores voluptate esse blanditiis laborum recusandae vitae et.</p>
			<p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Neque ab nulla similique! Aut vel molestiae nam eius excepturi, in tempore officia deleniti natus quae ipsam, unde nostrum odio consectetur quam.</p>
			<p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Earum ex veniam nam, sed, optio molestias, facere consectetur corrupti sint qui atque a, dolorum non minima expedita perferendis repudiandae esse natus.</p>
			<ul>
				<li>Lorem ipsum dolor sit amet</li>
				<li>Lorem ipsum dolor sit amet</li>
				<li>Lorem ipsum dolor sit amet</li>
				<li>Lorem ipsum dolor sit amet</li>
			</ul>
			 <iframe width="420" height="315" src="http://www.youtube.com/embed/m0_MNGa9RYI"></iframe> 
		</section>
		<!-- footer = balise permettant de délimiter le pied de page -->
		<footer>
		<p>Semere B.</p>
		<a href="mailto:binsem25@hotmail.com">binsem25@hotmail.com</a> <!-- mailto: permet d'envoyer un email quand on clique sur le lien -->
		</footer>
	</body>
</html>
