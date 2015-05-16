# mapCongo
<html>
	<head>
		<title>Travail  pratique</title>
		<link rel="stylesheet" href="style.css" />
		<meta http-equiv="Content-Type" content="text/html; charset=iso-8859-1" />
			<!-- Elément Google Maps indiquant que la carte doit être affiché
			en plein écran et
			qu'elle ne peut pas être redimensionnée par l'utilisateur -->
			<meta name="viewport" content="initial-scale=1.0, userscalable=no" />
			<!-- Inclusion de l'API Google MAPS -->
			<!-- Le paramètre "sensor" indique si cette application utilise
			détecteur pour déterminer la position de l'utilisateur -->
			<script type="text/javascript" src="http://maps.google.com/maps/api/js?sensor=false"></script>
			<script type="text/javascript">
			function initialiser() {
			var latlng = new google.maps.LatLng(0.5236565,25.1921225);
			//objet contenant des propriétés avec des identificateurs prédéfinis dans Google Maps permettant
			//de définir des options d'affichage de notre carte
			var options = {
			center: latlng,
			zoom: 10,
			mapTypeId: google.maps.MapTypeId.ROADMAP
			};
			//constructeur de la carte qui prend en paramêtre le conteneur

			//dans lequel la carte doit s'afficher et les options
			var carte = new
			google.maps.Map(document.getElementById("carte"), options);
			}
		</script>
	</head>
	<body onload="initialiser()">
		<div  id="page">
					<div id="banniere">
						<h1 id="sujet"> BIENVENUE A KISANGANI </h1>
		            </div>
					<div  id="milieu">
							<div id="milieu_gauche">
								<img id="image" src="Kisangani_01.jpg" alt="mon image favorite"/><br/>
								<img id="image" src="VUE.jpg" alt="mon image favorite"/><br/>
								<img id="image" src="Kisangani_cathédrale.jpg" alt="mon image favorite"/><br/>
								<img id="image" src="Universite-de-kisangani.jpg" alt="mon image favorite"/><br/>
								<img id="image" src="lemaireetsullivan3.jpg" alt="mon image favorite"/><br/>
								<img id="image" src="FTO.jpg" alt="mon image favorite"/><br/>
								<img id="image" src="FLEUVE.jpg" alt="mon image favorite"/><br/>
								<img id="image" src="kisangani.jpg" alt="mon image favorite"/>
		                    </div>
							<div id="milieu_centre">
								<div id="milieu_centre1"> 
					<a id="sujet" href=page2.html> accueil</a>
					<a id="sujet" href=page3.html> actualités </a>
					<a id="sujet" href=page4.html> revues  </a>
								</div>
								<div id="carte" >
								
								</div>
		                    </div>
							<div id="milieu_droit">
								<p id="texte">
								            L'île est située à quelques mètres de la rive du site de la ville actuelle, sur la 
								rivière Lualaba qui est un ensemble de 7 chutes réparties sur 100 km entre Kisangani et Ubundu. 

Après la fondation du poste, Stanley y a laissé M. Adrien Binnie<!--, un ingénieur Ecossais en charge d'entretenir des relations 
commerciales avec les autochtones et représenter l'Etat Indépendant du Congo. Dans la même période,-->. Les esclavagistes "Arabes" 
venues de Zanzibar, atteignent Stanleyfalls avec à leur tête Mohamed Bin Alfan Mujreb alias "Tippo Tip". 
<!--Les relations entre les fonctionnaires de l'Etat Indépendant et les arabes se compliquent, des combats sont engagés et 
après de lourdes pertes, le Poste a été abandonné en 1887 au profit des esclavagistes. 
-->
En 1888, l'Etat Indépendant obtient (après des négociations à Zanzibar) une entente pour l'établissement d'une forme de 
pouvoir, en nommant Tippo Tip (l'un des plus grands chefs esclavagistes de Zanzibar), comme premier gouverneur du district 
de "Stanleyfalls" qui s'étend de l'Est Tanganyika à l'Ituri en passant par le Maniema. 
Le 15 juillet 1898, le district de Stanleyfalls devient Province Orientale avec comme chef lieu Stanleyville, qui obtient
 le statut de ville grâce à l'ordonnance Nº12/357 du 06 septembre 1958, qui la divisait en 4 communes : Belge I 
 (Mangobo et Tshopo), Belge II (Lubunga), Bruxelles (Kabondo) et Stanley (Makiso). 

<!--Vers la fin de l'année 1958, la ville est devenue la forteresse de Patrice Emery Lumumba, qui y lance le Mouvement 
National Congolais (MNC). Après l'assassinat de Lumumba en 1961, Antoine Gizenga y a installé un gouvernement qui a
 rivalisé avec le gouvernement central de Leopoldville (maintenant Kinshasa). 

Le régime de Gizenga a été brisé en 1962, mais de 1964 à 1967, la ville a été le théâtre de troubles sanglants, avec
 les grandes exécutions publiques des autorités insurgées (16 condamnés), à la place des martyrs en 1964. 

En août 1964, le Gouvernement Gbenye Christophe s'installe à Kisangani et est reconnu par 7 pays dont l'ancienne URSS 
et l'Egypte. Le 24 novembre la ville est reprise par les parachutistes belges. Le 23 juillet 1966, les gendarmes katangais
 (Diabos) se mutinent. Le 5 juillet 1967, les mercenaires conduits par Bob Denard et Jean Schramme se mutinent à leur tour.
 Le 27 juillet de la même année, un cessez-le-feu est obtenu entre les Diabos et les mercenaires, sous l'impulsion du premier
 ministre Général de Brigade Léonard Mulamba, accompagné du Ministre de l'intérieur Tshisekedi wa Mulumba. 
-->
Avec la politique d'authenticité du Président Mobutu, Stanleyville devient Kisangani, Stanleyfalls, chutes Wagenya, et 
les communes furent rebaptisées de leur nom actuel, le 27 octobre 1977. 

D'une superficie de 1910 km², la ville de Kisangani a une densité de 229 habitants/km². 

<!--La ville de Kisangani est située à 0º31' de latitude Nord, par rapport à l'Equateur, 25º11' de longitude Est par rapport 
au méridien de Greenwich, et 428 mètres au dessus du niveau de la mer. 
-->
Situé à 324 km de Buta, 572 km d'Isiro, 696 km de Bunia et 2912 km de Kinshasa, Kisangani est limitée au Nord par les
 territoires de Banalia et Bafwasende, au Sud par le territoire d'Ubundu, à l'Ouest par le territoire d'Isangi au Pk. 18 sur la rive droite du fleuve et au Pk. 25 sur la rive gauche du fleuve, au niveau de la localité de Yalisombo et celui d'Opala au Pk 36. 

La ville de Kisangani, est traversée par la rivière Tshopo et est située le point de jonction entre le Lualaba et le 
fleuve Congo.<!-- Cette abondance de cours d'eau permet à la population de Kisangani de se déplacer et de transporter facilement des marchandises en baleinière, pirogue à pagaie ou motorisée, d'une rive à l'autre et d'un quartier à l'autre. Kisangani constitue de ce fait le plus haut point navigable sur le fleuve Congo et donc le terminus de la navigation fluviale à partir de Kinshasa et de tous les ports de l'ONATRA.

Cependant, le moyen de transport le plus utilisé est le taxi vélo communément appelé "Toleka" dans une ville 
où seules les organisations Internationales et des particuliers possèdent des voitures ou des motos. 
Le centre ville dispose d'une artère routière asphaltée parsemée de nids de poule par manque d'entretien. Les
 autres artères de la ville, en latérite, sont très poussiéreuses et généralement mal entretenues. 

Les routes de Kisangani ne permettent plus comme jadis de se rendre dans l'Ituri, à Opala, dans le Bas-Uele, au Sud Kivu
 et au Maniema. 

Kisangani dispose aussi d'une gare de chemins de fer gérée par la Société Nationale des Chemins de Fer du Congo. 

Kisangani possèdent deux aéroports, dont l'un international, avec sa piste de 3 800 mètres, est situé à Bangboka 
et l'autre, militaire et secondairement civil, situé à "Simisimi". 
-->

<!--Patrimoine 

Le monument populaire Stanley a été détruit et son socle transformé en fontaine publique qui abreuve les habitants des environs ainsi que tous les passants assoiffés. 

Les chutes Wagenia où la pêcherie est installée sur les rapides sont à voir. La pêche y est pratiquée grâce à un échafaudage planté au milieu des roches, avec des lianes fixées aux travers et servant de tendeur aux nasses de lianes tissées en forme de cône, immergées dans les eaux coulantes du fleuve. 

Le jardin zoologique, sur la rive droite de la rivière Tshopo attire de nombreux visiteurs, tout comme le barrage hydroélectrique qui alimente la ville de Kisangani. 

Kisangani a le troisième grand campus de l'Université National du Congo, mais aussi des instituts supérieurs d'enseignement technique et un musée. 

Les bâtiments sont anciens, d’influence belge avec des toitures en tuiles. 
-->

<!--Habitants 

Le dernier recensement de 2003 dénombrait près de 672 739 habitants dans la ville de Kisangani. Lubunga, est la commune la plus peuplée mais la moins dense avec 115 775 habitants, tandis que Mangobo avec 98 434 habitants, est la plus dense. 

La population autochtone est composée de Wagenia et de Kumu, mais la ville a une population hétérogène de plus de 250 ethnies majoritairement repartie comme suit: 
• Vers le nord de la ville (commune de la Tshopo), vivent les Bamanga, les Popoï, les Boa, venus par la route de Buta. 
• Vers le sud (commune de la Lubunga), se trouvent les Lokele, Turumbu, Mbole, Kumu, Wagenia, Rega (ces dernières sont arabisées) populations venues du Maniema par la route d'Ubundu et le chemin de fer ainsi que par la route Opala et le fleuve en direction du territoire voisin d'Isangi. 
• Vers l'ouest (commune de Mangobo), il y a les Topoke, Lokele, Turumbu, les Basoko arrivés par le fleuve Congo et la rivière Tshopo qui, elle aussi, divise la commune Tshopo en deux rives. 
• Vers l'est (commune de Kabondo), on trouve les Bali, Lendu, Budu, Bangetu, Logo, Alur, Hema, Nande, Yira venus par la route de l'Ituri débouchant à Bunia. 
Les principales langues parlées sont le lingala et le swahili, hormis le français, la langue officielle du pays. 
Titres administratifs 

Kisangani, autrefois Stanleyville, capitale de la Province Orientale, est une ville située au nord-est de la RD Congo, implantée sur les deux rives du fleuve Congo, à partir des chutes Stanley. La ville est desservie par une voie ferrée et deux aéroports. Kisangani est aussi le terminus du bief navigable du fleuve Congo de Kinshasa à Kisangani. C'est un centre de transbordement et de manufacture. C'est aussi une ville universitaire: elle abrite notamment l'Université de Kisangani et plusieurs institutions d'enseignements supérieurs. 
Un poste y avait été établi en 1882, près du site de l'actuel Hôtel de Ville, par l'explorateur anglo-américain Sir Henry Morton Stanley. Stanleyville, devenue une ville en 1898, est renommée Kisangani en 1966. Sa population est d'environ 672 739 habitants. 

Chef-lieu de la province Orientale, Kisangani est subdivisée en six communes: Makiso, Tshopo, Mangobo, Kabondo, Kisangani (sur la rive droite du fleuve Congo) et Lubunga (sur la rive gauche). Les six communes de la ville sont divisées en 67 quartiers. La collectivité-secteur de Lubuya Bera fait aussi partie des entités de la ville de Kisangani. 
-->
<!--Activités socio-économiques 

Troisième ville économique du Congo, Kisangani est le poumon économique de la province. 

Les atouts de son réseau de transport (qui laisse à désirer aujourd'hui) ont contribué au développement des services et des industries textiles, métallurgiques, hydroélectriques. On y compte aussi des scieries, une usine brassicole, une savonnerie et des entreprises de décorticage artisanal du paddy ainsi que du café. 

En effet, la Société Nationale d'Electricité dispose d'une centrale Hydroélectrique sur la rivière Tshopo mais seule une turbine sur les trois dont dispose le barrage fonctionne. La société Textile de Kisangani (SOTEXKI) produit des tissus et confectionne des habits, mais elle connaît d'énormes difficultés d'approvisionnement en coton en raison du mauvais état des routes. 

La BRALIMA produit des boissons sucrées et alcoolisées, la REGIDESO traite et fournit de l'eau aux populations, la Société de Gestion, de Gérance et d'Investissement (SORGERIE), en état d'arrêt depuis le début de la guerre, produit du savon, l'huile végétale ainsi que d'autres produits cosmétiques. La Compagnie Forestière de Transformation (CFT) et la BEGO-Congo coupent, transforment et exportent le bois. 
Le secteur informel est aussi très développé dans les productions artisanales et les briqueteries (fabrication de briques en terre cuite). 

Toutes ces industries fonctionnent difficilement en raison de la vétusté des équipements, des sources d'approvisionnement et des problèmes électriques que connaît la ville. La plupart fonctionnent grâce à des groupes électrogènes. 

Le sous-sol de Kisangani est riche en diamant et en or. Cette richesse n'est pas exploitée. Le diamant vendu dans les comptoirs de la ville provient des territoires de Banalia, Bafwasende, d'Opala, et d'Isangi. 

Les produits vivriers proviennent des villages environnants dont les activités principales sont l'agriculture et l'élevage du bétail. Kisangani reste aussi célèbre pour ses fameux «Kosa Kosa», grosses crevettes exportées dans toutes les grandes villes de la RD Congo et principalement à Kinshasa. La plupart des produits manufacturés sont importés des provinces voisines et particulièrement de Kinshasa et de l'Est du pays. 

La voie fluviale est à Kisangani le seul moyen de transport permettant l'acheminement des marchandises d'une zone à une autre, les importations et les exportations. 

Toutes les communes de la ville ont un surnom dénotant la manière dont les Boyomais perçoivent leurs cités. 

C'est ainsi que Kisangani (qui signifie en swahili sur l'île; "Kisanga": Ile et "ni": sur) est dénommée par les autorités administratives "ville d'espoir" pour l'opposer à la ville martyre qu'elle était, tandis que les Boyomais l'appellent affectueusement "Boyoma Singa-Mwambe" (Boyoma signifie la plus belle fille, Singa le mât et Mwambe 8: ce qui veut dire qu'il faut jeter 8 fois le mât avant d'atteindre la plus belle ville). 

La commune de Kisangani s'appelle communément "Tolimo" en Kigenia (en raison des échafaudages artisanaux installés sur les chutes Wagenia). 

Mangobo est dénommé "Mathématique" en raison des difficultés à trouver une adresse dans des rues qui ne portent pas de noms mais dont les parcelles sont numérotées. 

Makiso "Miroir" est la commune où est située le centre ville avec ses industries, ses centres commerciaux et son marché central. Le centre-ville est alimenté sans interruption en eau et en électricité parce qu'il abrite les plus belles maisons, les plus belles avenues, la mairie, le gouvernorat et autres structures administratives ainsi que les sièges locaux d'ONG et d'organisations internationales. 
Lubunga "pays" est la commune urbano-rurale, elle alimente la ville en produits vivriers. 

Kabondo "Pilote" est la commune qui prend toujours les devants de toutes les manifestations publiques. -->
								
								</p>
		                    </div>
		            </div>
					<div  id="footer">
					<p="sujet">Copyright@ Mbuyu Kalumba Michael and Mulongo Kasongo Vanessa</p>
		            </div>
		</div>
	</body>
	// page css
	
	#page
{
width:1200px;
height:900px;
background-color:blue;
margin:auto;
}
#banniere
{
width:1200px;
height:200px;
background-color:fuschia;
margin:auto;
 
}
#sujet{
font-style:italic;
font-weight:bold;
text-align:center;
}
#milieu
{
width:1200px;
height:800px;
background-color:purple;
margin:auto;
}
#milieu_gauche
{
width:210px;
height:800px;
background-color:pink;
float:left;
}
#image{
width : 210px;
height :100px;
}
#milieu_centre
{
width:680px;
height:800px;
background-color:rgb(230,0,230);
float:left;
}
#milieu_centre1
{
width:680px;
height:50px;
background-color:rgb(191,0,191);
padding-top:0px;
}
#carte
{
width:680px;
height:750px;
background-color:white;
  
}
 #milieu_droit
{
width:310px;
height:800px;
background-color:purple;
 float:left;
}

#footer
{
width:1200px;
height:50px;
background-color:rgb(81,0,81);
margin:auto;
//propriete unitile
color:white;
}
#texte
{
text-align:right;

}
</html>
