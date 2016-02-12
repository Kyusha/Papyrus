# Papyrus
Maison des ligues by Papyrus

<html lang="en">
  <head>
    <meta charset="utf-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <meta name="description" content="">
    <meta name="author" content="">
    <link rel="icon" href="../../favicon.ico">

    <title>Maison des ligues</title>

    <!-- Bootstrap core CSS -->
    <link href="css/bootstrap.css" rel="stylesheet">

  </head>

  <body>
  <div id="body">
  <header>
  <center>
  
                <div id="titre_principal">
                    <div id="logo">
                        
                         
						<img src="Papyrus.png" alt="MDL"  width= 180px; />
						
                    </div>
    <div class="navbar navbar-default navbar">
      <div class="container">
        <div class="navbar-header">
          <button type="button" class="navbar-toggle collapsed" data-toggle="collapse" data-target="#navbar" aria-expanded="false" aria-controls="navbar">
            <span class="sr-only">Toggle navigation</span>
            <span class="icon-bar"></span>
            <span class="icon-bar"></span>
            <span class="icon-bar"></span>
          </button>
          <a class="navbar-brand" href="test.php">ACCUEIL</a>
        </div>
        <div id="navbar" class="collapse navbar-collapse">
          <ul class="nav navbar-nav">
		   <li class="dropdown">
             <a data-toggle="dropdown" class="dropdown-toggle" href="#">Présentation M2L<b class="caret"></b></a>
			 <ul class="dropdown-menu">
                            <li><a href="PresentationServices.php">Services Proposés</a></li>
                            <li><a href="Locaux.php">Locaux</a></li>
                            <li><a href="Matos.php">Matériels informatiques</a></li>
                        </ul>
                    </li>
			<li><a href="ligue.php ">Ligues hébergées</a></li>
            <li><a href="#">Réservations</a></li>
			<li><a href="Connexion.php">Connexion</a></li>
          </ul>

        </div><!--/.nav-collapse -->
      </div>
    </div>
	<br /><center><div class="container" ><h4><strong>Services proposés aux ligues par la M2L :</strong></h3><br /><br />

<div class="well"><h4><i>Accès Internet : </i></h4>
<p>Les ligues disposent d'un accès Internet mutualisé que la M2L loue à un prestataire extérieur.
</p></div><div class="well"><i><h4>Accès Wifi :</i></h4>
<p>Dans tous les espaces, un réseau Wifi "visiteurs" est disponible, avec une clé WPA renouvelée régulièrement et communiquée aux ligues. Ce réseau ne permet que l'accès à Internet.
</p></div><div class="well"><h4><i>Téléphonie :</i></h4>
<p>Dans les bâtiments anciens A et B, les salles et bureaux sont équipés de prises de téléphone analogiques. La M2L y fournit les combinés téléphoniques. Dans les bâtiments neufs C et D, l'équipement téléphonique est de type VoIP. La M2L loue des postes téléphoniques IP aux ligues.
</div><div class="well"></p><h4><i>Affranchissement :</i></h4>
<p>Une machine à affranchir permet un affranchissement rapide et en nombre. Cette prestation est facturée aux ligues au coût de l'affranchissement. Chaque mois, on relie la machine à affranchir à une imprimante pour obtenir une liste de codes de gestion correspondant aux ligues associés à une quantité et un type d'affranchissement. 
La prise en compte de ces informations permet au CROSL d'éditer des factures.
</p></div>
<div class="well"><h4><i>Impressions en volume et en qualité imprimerie :</i></h4>
Les ligues disposent de la possibilité d'imprimer sur des ressources d'impression numériques connectées situées dans le local reprographie du rez-de-chaussée dont l'usage fait l'objet d'une facturation à prix coûtant. Un système de comptage situé sur le serveur d'impression permet au CROSL d’effectuer une facturation mensuelle auprès des ligues.<br />
•	une photocopieuse noir et blanc à 70 pages/minute avec différents dispositifs de finition,<br />
•	une imprimante Laser couleur A4/A3 à encre solide à 25 pages/minute,<br />
•	un traceur A2 (1 page / minute) utilisé pour les affiches et banderoles.<br />
</div>
<div class="well"><h4><i>Serveur FTP documentaire :</i></h4>
La M2L met à disposition des ligues un serveur FTP documentaire intranet/internet regroupant des textes légaux, des modèles de dossiers, de statuts, des programmes de formation (...) compilés par le CROSL.
</div>
<div class="well"><h4><i>Système de réservation des salles :</i></h4>
La M2L met à disposition des ligues un site web de réservation des salles (réunions, amphithéâtre, restauration). Ce site est accessible en intranet, mais aussi depuis l'internet. Les réservations payantes sont facturées par la Région aux utilisateurs. L’administration de la M2L lui communique les informations nécessaires à cette facturation de façon hebdomadaire.
</div>
<div class="well"><h4><i>Information sur le digicode du jour et la clé Wifi :</i></h4>
La M2L met à disposition des ligues un site web d'information sur le digicode permettant l'accès à la M2L ainsi que sur la clé Wifi "visiteurs". Le système de réservation donne également le digicode du jour dans le compte-rendu de réservation envoyé automatiquement par mail.
Système de gestion des configurations
M2L gère à travers un logiciel de gestion des configurations l'ensemble du parc informatique incluant les postes fixes des ligues.
</div>
<div class="well"><h4><i>Intégration des postes informatiques des ligues :</i></h4>
Lorsque les ligues acquièrent du matériel informatique, il y a une phase obligatoire d'intégration qui consiste à :<br />
•	installer un antivirus affilié au serveur antiviral de la M2L,<br />
•	installer la dernière version de l'agent qui réalise l’inventaire matériel et logiciel<br />
•	paramétrer le poste en adressage IP automatique,<br />
•	installer un système de sauvegarde de données sur un site FTP de sauvegarde géré par la M2L,<br />
•	effectuer les dernières mises à jour systèmes et à paramétrer leur automatisation,<br />
•	paramétrer les noms des postes selon les règles de gestion suivantes :<br />
B[code bâtiment]E[numéro étage]L[numéro ligue]S[numéro salle].P[numéro poste]<br />
Code bâtiment qui peut être A ou C<br />
N° étage est compris entre 1 et 4 (puisque les locaux du rez-de-chaussée n'hébergent pas de ligues)<br />
N° ligue sur 2 chiffres : correspond à un nombre attribué à la ligue allant pour l'instant de 01 à 24<br />
N° salle sur 2 chiffres : correspond aux bureaux occupés par les ligues<br />
N° poste sur 2 chiffres : correspond au numéro écrit sur la prise murale<br />
Exemple : le nom d'hôte BAE2L06S01P01 correspond au poste installé sur la prise N°1 du bureau A201 occupé par la ligue de Volley,<br /> bureau situé au deuxième étage du bâtiment A. <br />
Cette intégration est contractualisée. Les ligues et CD étant toutes des structures associatives indépendantes, leurs postes ne sont pas intégrés dans un annuaire central. Par contre, les postes de l'administration de la M2L et de la salle multimédia le sont.<br />

</div>
<div class="well"><h4><i>Intégration d'imprimantes :</i></h4>
Lorsque les structures hébergées s'équipent d'imprimante réseau, la connexion en est réalisée par l'informaticien bénévole du CROSL, sans passer par un serveur d'impression. Le nom de l'imprimante est lui aussi codifié de la même façon que celui des postes (la lettre L vient remplacer la lettre P).
</div>
<div class="well"><h4><i>Service d'établissement de bulletins de salaire :</i></h4>
Le CRIB (Centre Régional d'Information des Bénévoles) est un label donné au CROSL qui, entre autres missions d'information (sur les textes réglementaires, la convention nationale du sport ...), propose un service d'établissement de bulletins de salaires aux ligues et à leurs clubs affiliés.
 Le CROSL est tiers de confiance pour l'URSSAF et, à ce titre, établit des bulletins de salaires réglementaires et tous les documents annexes. La prestation est facturée au forfait (60 € par an) et au bulletin édité (5 €). Un employé du CROSL est affecté à cette mission à raison de 0,8 ETP.<br /><br />

Illustration du processus pour une ligue qui fait établir ses bulletins de salaires par le CRIB, pour des animateurs à la vacation, comme pour ses employés permanents.<br />

- La ligue établit une « déclaration unique d'embauche » et un contrat de travail.<br />

- Les données "salaires" sont envoyées par les associations au CRIB avant le 15 du mois :<br />
-	Nom, prénom, date de naissance, adresse, n° de sécu, de l’intervenant ou du salarié<br />
-	Dates et heures d'intervention (de jour / de nuit)<br />
-	Heures congés payées associées<br />
-	Taux horaire<br />
-	Intitulé dans la grille de la convention nationale du sport (exemple : technicien niveau 3)<br />

En retour, le CRIB fournit le bulletin de salaire et le document sur les charges périodiques.<br />

Le salaire est viré par la ligue, si celle-ci a fait ce choix. Sinon il y a un prélèvement sur son compte et virement sur le compte du salarié.<br />

Pour les versements aux organismes sociaux, il y a prélèvement direct sur le compte de la ligue. 
</div>
<div class="well"><h4><i>Formations :</i></h4>
Le CROSL offre un catalogue diversifié de formations aux bénévoles des clubs affiliés aux ligues (législation, éthique, comptabilité associative, etc.). Les ligues organisent également des formations, en général plus techniques, sur l'usage de logiciels spécifiques de gestion des clubs ou des compétitions sportives.
</div>
</div>	
	
	
	
	
	
	
	</div>
	
	<footer>
    <button type="button" class="btn btn-primary" href="Contact.php" data-toggle="modal" data-target=".bs-example-modal-lg1">Contact</button>
<div class="modal fade bs-example-modal-lg1" tabindex="-1" role="dialog" aria-labelledby="myLargeModalLabel">
  <div class="modal-dialog modal-lg">
	<div class="modal-content">
  	
	</div>
  </div>

</div>
    <button data-toggle="modal"href="Emploi.php" data-target=".bs-example-modal-lg2"  class="btn btn-primary"  >Emploi</button>
<div class="modal fade bs-example-modal-lg2" tabindex="-1" role="dialog" aria-labelledby="myLargeModalLabel">
  <div class="modal-dialog modal-lg">
	<div class="modal-content">
  	...
	</div>
  </div>

</div>
     <button data-toggle="modal" href="Personnels.php"  data-target=".bs-example-modal-lg3" class="btn btn-primary">Qui sommes-nous ?</button>
<div class="modal fade bs-example-modal-lg3" tabindex="-1" role="dialog" aria-labelledby="myLargeModalLabel">
  <div class="modal-dialog modal-lg">
	<div class="modal-content">
  	...
	</div>
  </div>

</div>
<button data-toggle="modal"href="remote.php" data-target="#infos" class="btn btn-primary">Mentions légales</button><br /><br />

<div class="modal fade" id="infos">

  <div class="modal-dialog modal-lg">

	<div class="modal-content">

  	<div class="modal-header">

    	<button type="button" class="close" data-dismiss="modal">x</button>

	</div>

  </div>

</div>


 </footer>

			
   
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/1.11.1/jquery.min.js"></script>
    <script src="js/bootstrap.min.js"></script>
    <script src="js/ie10-viewport-bug-workaround.js"></script>
  </body>
</html>
