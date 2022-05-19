## I started this project on 23/02/2021
*Training begins on 23/12/2020*

17.03.2021

* Mise en place de la branche "feature".
* L'animation des coeurs ---ok
* Le hover des fonctionnalités ---ok (utilisations de opacity pour le hover)
* Les bouton s'éclaircissent en hover (utilisation de opacity)
* En cours de réa sur les animations "check boxes"...
  -première étape----ok

18.03.2021

* Réa de toute les animations----> ok.
  - Modifications à prévoir pour le "loading-spinner"(faire basculer cette ```<div>``` et non le ```<main>```)
* Prévoir une modification en html = la balise ```<main>``` doit être, entre le ```<header>``` et le ```<footer>```.
* Mettre en place le responsive du site. 
* Petite erreur sur le w3c html sur les pages secondaires (balise ```<div>```dans le ```<h2>``` à changer en ```<span>```) 

19.03.2021

* Modification sur le "loading spinner", c'est le loading qui disparait et non le bloc main.
* Les balises "main" se trouvent maintenant entre le header et le footer.
* Ajout d'une "div" qui englobe toute la page (header, main et footer) pour mettre en place le loading.
	-cette div est en position absolute ---> pour palier au pb de taille des font.
* Correction apportée sur les pages: balise "span" au lieu de "div" dans le h2.

21.03.2021

* Debug de mon problème de dimension en cours...
  - impossible de faire le responsive correctement sans l'ajout de la balise:
    - ```<meta name="viewport" content="width=device-width, initial-scale=1.0">```
    - Besoin de revoir toutes les valeurs "rem" et de réajuster la mise en page";
* Index.html :------ok;

22.03.2021

* Fin du débug;
* Début du responsive; 

25.03.2021

* fin du responsive;
* modifications du loading-spinner;
* modifs sur la check box ----ok;
* revoir les bouton et les bloc fonctionnements ----> ! ne pas dupliquer les blocs !
 
27.03.2021

* retouches sur le responsive + ajout d'un hover sur les ```<li>```
* les blocs de la section fonctionnement ne sont plus dupliqués.
* Les boutons aussi ont été modifié. Eux aussi ne sont plus dupliqués.
* le bug des coeurs sur les pages a été corrigé. 

28.03.2021

* la checkbox a maintenant un "transition" à la place d'une animation;
  - grâce à cela on a un ":hover-out" qui fonctionne correctement
* la transition se fait maintenant grâce à un width et non une margin-left;

02.04.2021

* animation des dots du loading spinner + des animations menu réalisé avec des boucles !
* ajout du webkit-gradient pour les navigateurs qui ne traduisent pas linear-gradient.
* amélioration du logo du loading spinner (on ne distingue plus le bloc derrière lequel il
  diparait)