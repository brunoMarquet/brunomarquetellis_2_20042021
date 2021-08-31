# brunomarquetellis_2_20042021
test 2juillet
Bonjour
ci dessous vous ytrouverz le CR de validation de W3C,  avec des erreurs
---------
sur la page index.html en cliquant sur le lien d " à propos"  vous pourrez rvoir un certain nbre de page additiàonnelles (décrites tout en bas, ci dessous)
merci

_______

Compte Rendu de validation de W3C
_______

index;html:


a Informations (1)
Document soumis	a
HTTP resource not retrievable. The HTTP status from the remote server was: 404.	a
Erreurs2 Avertissements22 a Ce document n'a pas réussi le test : W3C Validateur CSS (Niveau 3) Lien direct
a Erreurs (2)
Fichier : https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.1/css/all.min.css	a
5		.fa, .fab, .fad, .fal, .far, .fas	La propriété “text-rendering” n'existe pas : auto	a
Fichier : file://localhost/css_P2.css	a
Erreur inconnue java.lang.Exception: import file://localhost/css_P2.css: Operation not permitted	a
(car verification par fichier individuel, sur mon DD)
a Avertissements (22)
Fichier : file://localhost/index.html	a
12			Vous devriez ajouter un attribut 'type' ayant pour valeur 'text/css' à l'élément 'link'	a
17			Vous devriez ajouter un attribut 'type' ayant pour valeur 'text/css' à l'élément 'link'	a
19			Vous devriez ajouter un attribut 'type' ayant pour valeur 'text/css' à l'élément 'link'	a
Fichier : https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.1/css/all.min.css	a
5			La propriété “-moz-osx-font-smoothing” est une extension propriétaire inconnue	a
5			La propriété “-webkit-font-smoothing” est une extension propriétaire inconnue	a
5			La propriété “-webkit-animation” est une extension propriétaire inconnue	a
5			La propriété “-webkit-animation” est une extension propriétaire inconnue	a
5			La règle-arobase “@-webkit-keyframes” n'est pas reconnue	a
5			La propriété “-webkit-transform” est une extension propriétaire inconnue	a
5			La propriété “-webkit-transform” est une extension propriétaire inconnue	a
5			La propriété “-ms-filter” est une extension propriétaire inconnue	a
5			La propriété “-webkit-transform” est une extension propriétaire inconnue	a
5			La propriété “-ms-filter” est une extension propriétaire inconnue	a
5			La propriété “-webkit-transform” est une extension propriétaire inconnue	a
5			La propriété “-ms-filter” est une extension propriétaire inconnue	a
5			La propriété “-webkit-transform” est une extension propriétaire inconnue	a
5			La propriété “-ms-filter” est une extension propriétaire inconnue	a
5			La propriété “-webkit-transform” est une extension propriétaire inconnue	a
5			La propriété “-webkit-transform” est une extension propriétaire inconnue	a
5			La propriété “-ms-filter” est une extension propriétaire inconnue	a
5			La propriété “-webkit-transform” est une extension propriétaire inconnue	a
5			La propriété “-webkit-filter” est une extension propriétaire inconnue	a
Informations1 a Résultats pour le test : Feed Validator Lien direct
----------------
css
--------------------
css avertisseme
---------------
e fichier» et «saisie directe», le validateur ne vérifie pas les feuilles de style importées.	a
12			La propriété “--color_bleu_1” est une extension propriétaire inconnue	a

c'est une variable !

379		.annonce_1	“background-color” et “border-top-color” sont de la même couleur	a
379		.annonce_1	“background-color” et “border-right-color” sont de la même couleur	a
379		.annonce_1	“background-color” et “border-bottom-color” sont de la même couleur	a
379		.annonce_1	“background-color” et “border-left-color” sont de la même couleur

c'est expres poir avoir un cadre blanc autour de la miniature des hotels !

_____________
valid css:
<p>
	<a href="http://jigsaw.w3.org/css-validator/check/referer">
		<img style="border:0;width:88px;height:31px"
			src="//jigsaw.w3.org/css-validator/images/vcss"
			alt="CSS Valide !" />
	</a>
</p>
CSS Valide !
<p>
	<a href="http://jigsaw.w3.org/css-validator/check/referer">
		<img style="border:0;width:88px;height:31px"
			src="//jigsaw.w3.org/css-validator/images/vcss-blue"
			alt="CSS Valide !" />
	</a>
</p>

_____________
reflexions
______________

<li>
        réflexion- tip:1 page :page d'accueil ou resultat d'une requete sur Marseille?
dans le cas un(celui retenu) un placehoder...sur Marseille !
     dans le cas 2: il faudrait éventuellement placer une balise spécifique sur la "la ville de la requête ``  et les "500 hébergements".
     </li>
      
      <li>choix délibéré de ne pas surcharger les écritures dynamique (les 3 sections de la page) avec des div...?</li>
     <li>balises sémantiques: écriture d'une petite "css" pour les visualiser..</li>
     
     <li>pour le main qui englobe ou non les activités on peut discuter ??? </li>
     <li>les 3 sections de la page sont ou peuvent etre générées en javascript</li>
li>les positions des activités si générées en javascript ou en dynamique ?</li>
<li>filtres et "NRY(never repeat yaurself !)</li>
________
lien de la page " à propos" :
________________
1 -balises sémantiques: écriture d'une petite "css" pour les visualiser..
2 - contenu dynamique de la page en js
3 - étude sur les étoiles en css(before-after)
3 - lien nsur un iframe : pour le responsible)
4 - étude sur leformulaire ("simple", celui qui est présent sur la maquette !)
flexbox ... pour les etoiles
-en l'état- : étude II sur les formulaire(before-after) avec les 3 "variwants"- à finaliser!
-en l'état- :étude sur les formulaire(before-after): tiré d'un exemple de 3schools
