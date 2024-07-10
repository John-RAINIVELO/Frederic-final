<!DOCTYPE html>
<html lang="fr">
<head>
    <meta name="viewport" content="width=device-width" />
	<meta http-equiv="Content-Type" content="text/html; charset=utf-8" />
	<title>WordPress &#8250; À lire</title>
	<link rel="stylesheet" href="wp-admin/css/install.css?ver=20100228" type="text/css" />
</head>
<body>
<h1 id="logo">
	<a href="https://fr.wordpress.org/"><img alt="WordPress" src="wp-admin/images/wordpress-logo.png" /></a>
</h1>
<p style="text-align: center">Plateforme de publication sémantique personnelle</p>

<h2>Préambule</h2>
<p>Bienvenue. WordPress est un projet très spécial pour moi. Chaque contributrice et contributeur ajoute quelque chose d’unique à ce projet, et ensemble nous créons quelque chose de beau, et dont je suis fier de faire partie. Nous avons passé des milliers d’heures sur le développement de WordPress, et nous nous attachons tous les jours à vous faciliter la vie. Merci à vous d’en faire une partie de votre monde.</p>
<p style="text-align: right">&#8212; Matt Mullenweg</p>

<h2>Installation : la fameuse installation en 5 minutes</h2>
<ol>
	<li>Décompressez l’archive dans un dossier vide de votre ordinateur, puis mettez tous ces fichiers en ligne ;</li>
	<li>Ouvrez le fichier <code>wp-config-sample.php</code> avec votre éditeur de texte préféré, comme WordPad ou similaire, et complétez les informations liées à votre base de données ;</li>
	<li>Sauvegardez le fichier sous le nom <code>wp-config.php</code> ;</li>
	<li>Envoyez le tout sur votre hébergement via un logiciel client FTP ;</li>
	<li>Ouvrez le fichier <span class="file"><a href="wp-admin/install.php">/wp-admin/install.php</a></span> dans votre navigateur. Celui-ci vous guidera dans la création du fichier <code>wp-config.php</code>, qui contient les détails de connexion à votre base de données ;
		<ol>
			<li>Si cela ne fonctionne pas, ne vous inquiétez pas : certains hébergeurs n’autorisent pas la création de fichier. Ouvrez le fichier <code>wp-config.php</code> avec un éditeur de texte, et saisissez-y directement les détails de connexion à votre base de données ;</li>
			<li>Enregistrez le fichier sous le nom <code>wp-config.php</code> et mettez-le en ligne ;</li>
			<li>Ouvrez le fichier  <span class="file"><a href="wp-admin/install.php">wp-admin/install.php</a></span> dans votre navigateur ;</li>
		</ol>
	</li>
	<li>Une fois le fichier de configuration correctement rempli, l’installateur met en place les tables nécessaires à votre blog. Si vous obtenez une erreur, vérifiez le contenu du fichier <span class="file"><code>wp-config.php</code></span>, et réessayez. Si cela échoue encore une fois, rendez-vous sur les <a href="http://wpfr.net/support/">forums d’entraide</a> et soyez le plus précis possible dans vos explications. Si tout se passe bien, passez à l’étape suivante ;</li>
	<li><strong>Si vous n’avez pas précisé de mot de passe, notez bien celui qui vous est donné.</strong> Si vous n’avez pas précisé d’identifiant, ce sera <code>admin</code> ;</li>
	<li>Une fois l’installation terminée, le script d’installation vous renverra vers la <a href="wp-login.php">page de connexion</a>. Connectez-vous avec l’identifiant et le mot de passe précisés (ou générés) durant l’installation. Si le mot de passe a été généré pour vous, cliquez sur « Comptes »  pour le modifier.</li>
</ol>

<h2>Mise à jour</h2>
<h3>À l’aide de l’outil de mise à jour automatique</h3>
<p>Si votre version de WordPress est égale ou supérieure à 2.7, vous pouvez utiliser l’outil de mise à jour automatique&nbsp;:</p>
<ol>
	<li>Ouvrez la page <span class="file"><a href="wp-admin/update-core.php">wp-admin/update-core.php</a></span> dans votre navigateur, et suivez les instructions&nbsp;;</li>
	<li>Vous pensiez qu’il y aurait d’autres étapes ? C’est tout !</li>
</ol>

<h3>Mise à jour manuelle (obligatoire pour les versions de WordPress inférieures à 2.7) :</h3>
<ol>
	<li>Avant tout, assurez-vous bien de disposer de copies de sauvegarde de tous les fichiers que vous avez modifiés, par exemple <code>index.php</code>.</li>
	<li>Effacez vos anciens fichiers WordPress, sauf ceux que vous avez modifié, comme <span class="file"><code>wp-config.php</code></span> ou le contenu du dossier <span class="file"><code>/wp-content/</code></span>.</li>
	<li>Téléversez les nouveaux fichiers en provenance de l’archive de WordPress.</li>
	<li>Allez sur la page <code><span class="file"><a href="wp-admin/upgrade.php">/wp-admin/upgrade.php</a></span></code> avec votre navigateur internet.</li>
</ol>

<h2>Migrer depuis d’autres logiciels/plates-formes</h2>
<p>WordPress peut <a href="https://fr.wordpress.org/support/article/importing-content/">importer les articles en provenance de nombreux autres outils (en)</a>. Vous devez d’abord installer WordPress comme expliqué plus haut, puis utiliser <a href="wp-admin/import.php">un des outils d’import fournis</a>.</p>

<h2>Prérequis fonctionnels</h2>
<ul>
	<li><a href="https://secure.php.net/">PHP</a> version <strong>7.0</strong> ou plus.</li>
	<li><a href="https://www.mysql.com/">MySQL</a> version <strong>5.0</strong> ou plus.</li>
</ul>

<h2>Recommandations</h2>
<ul>
	<li><a href="https://www.php.net/manual/fr/intro-whatis.php">PHP</a> version <strong>7.4</strong> ou plus ;</li>
	<li><a href="https://www.mysql.com/fr/">MySQL</a> version <strong>5.6</strong> ou plus ;</li>
	<li>Module <a href="http://httpd.apache.org/docs/2.2/mod/mod_rewrite.html">mod_rewrite</a> d’Apache ;</li>
	<li>Prise en charge de <a href="https://wordpress.org/news/2016/12/moving-toward-ssl/">HTTPS (en anglais)</a> ;</li>
	<li>Ajouter un lien vers <a href="https://fr.wordpress.org/">wordpress.org</a> sur votre site.</li>
</ul>

<h2>Ressources en ligne</h2>
<p>Si vous vous posez des questions dont les réponses ne figurent pas sur ce document, vous disposez de nombreuses ressources en ligne :</p>
<dl>
	<dt><a href="https://fr.wordpress.org/support/">La documentation officielle <i lang="en">HelpHub</i> en français</a></dt>
		<dd><i lang="en">HelpHub</i> est l’encyclopédie liée à tout le fonctionnement de WordPress. Il s’agit de la source d’informations la plus complète qui soit.</dd>
	<dt><a href="https://wordpress.org/news/">Les actualités de l’écosystème WordPress</a></dt>
		<dd>C’est ici que vous trouverez les dernières informations, les annonces et les nouveautés de WordPress. Les derniers articles de ce blog sont affichés dans le Tableau de Bord de WordPress par défaut.</dd>
	 <dt><a href="https://planet.wordpress.org/"><i lang="en">WordPress Planet</i> (en anglais)</a></dt>
		<dd><i lang="en">WordPress Planet</i> est un agrégateur de news qui distille les articles de plusieurs blogs WordPress à travers le web.</dd>
	<dt><a href="http://wpfr.net/support/">Le forum d’entraide WordPress Francophone</a></dt>
		<dd>Si vous avez cherché partout et que malgré cela vous n’avez trouvé aucune réponse, les forums sont très actifs et son immense communauté sera prête à vous aider. Pour un traitement efficace de votre problème, faites en sorte d’utiliser, lors de la création de votre sujet, un titre et une description aussi pertinents et clairs que possible.</dd>
	 <dt><a href="https://codex.wordpress.org/IRC">Le canal <abbr title="Internet Relay Chat">IRC</abbr> WordPress</a></dt>
		<dd>Il existe un canal IRC qui est le rendez-vous des utilisateurs WordPress, et occasionnellement, propose son aide aux sujets liés à l’entraide. La page Wiki devrait vous indiquer la bonne direction.</dd>
</dl>

<h2>Pour finir</h2>
<ul>
	<li>Si vous avez des suggestions, des idées, des commentaires ou si vous avez trouvé un bug (oups !), venez nous rejoindre sur les <a href="https://wordpress.org/support/">forums anglophones (en anglais)</a>.</li>
	<li>WordPress possède une <abbr title="Application Programming Interface">API</abbr> d’extension robuste, qui permet d’étendre les possibilités de son code de manière simple. Si vous êtes un développeur intéressé par son utilisation, rendez-vous sur la <a href="https://developer.wordpress.org/plugins/">documentation à destination des développeur·euse·s d’extensions (en anglais)</a>. Vous ne devriez normalement pas avoir à modifier le code original de WordPress pour arriver à vos fins.</li>
</ul>

<h2>Faites connaître WordPress !</h2>
<p>WordPress ne possède pas une tonne de millions de dollars pour s’offrir une campagne marketing, ni de célèbres sponsors, mais nous avons bien mieux : VOUS. Si vous appréciez WordPress, n’hésitez pas à en parler à votre entourage, vos amis, en aidant d’autres personnes ayant un niveau inférieur au vôtre, ou encore écrire un article faisant référence à notre travail.</p>

<p>WordPress est la reprise officielle de <a href="http://cafelog.com/">b2/cafélog</a>, provenant de Michel V. Le travail a continué d’être assuré par <a href="https://fr.wordpress.org/about/">les développeuses et les développeurs de WordPress</a>. Si vous voulez apporter votre soutien à WordPress, n’hésitez pas à <a href="https://wordpressfoundation.org/donate/">faire un don (en anglais)</a>.</p>

<h2>Licence</h2>
<p>WordPress est un logiciel libre, mis à disposition sous les termes de la licence <abbr title="GNU Public License">GPL</abbr> version 2, ou de toute version suivante, au choix (voir <a href="license.txt">license.txt (en anglais)</a>.</p>

</body>
</html>
