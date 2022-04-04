# Mode d'emploi API - Auteurs
Dernière Mise à jour : 2022-01-24

### Ajouter un Auteur
![Alt text](/img/api_auteurs_1.png "a title")

* Vérifier grâce à la barre **Recherche** que l'auteur n'est pas encore saisi. Vous êtes nombreux à utiliser l'API. Évitons les doublons.

* Si vous ne trouvez rien, clicker sur le boutton **Nouvelle Entrée**

![Alt text](/img/api_auteurs_2.png "a title")

* Saisir le champ **Nom** avec Prénom et Nom dans cet ordre.
* Le champ **Tri selon** permet de choisir à quelle lettre l'auteur apparaîtera dans les liste alphabétiques. Si le champ est vide il ne sera pas pris en compte.
Si l'on saisi Prénom Nom, l'auteur sera classé à la lettre **P** (Prénom) hors il est important de pouvoir le classer à la lettre **N** (Nom). Il est donc important de stipuler le **Nom** de l'auteur. Il peut aussi être suivi du **Prénom** mais ce n'est pas obligatoire.

![Alt text](/img/api_auteurs_3.png "a title")

* Ajouter la biographie en Français et en Anglais. Le champ texte permet d'éditer le contenu en ajoutant des éléments en *italique*, **Gras**. Il permet aussi l'ajout d'un [hyperlien](url).

  L'éditeur est en MARKDOWN, mais c'est aussi possible d'ajouter du HTML. Notamment pour ajouter un hyperlien qui s'ouvre dans une nouvelle fenêtre : ``<a href="url" target="_blank">hyperlien</a>``

Bref rappel de notions :

 * Markdown :
    * ``*Italique*``
    * ``**Gras**``
    * ``[hyperlien](url)``
    >attention ne permet pas l'ouverture dans une nouvelle fenêtre

 * Html :
    * ``<em>Italique</em>``
    * ``<b>Gras</b>``
    * ``<a href="url" target="_blank">hyperlien</a>``
    ><a href="https://reseau-dda.org" target="_blank">exemple</a> ``<a href="https://reseau-dda.org" target="_blank">réseau documents d'artistes</a>``


![Alt text](/img/api_auteurs_4.png "a title")

* Pour valider la création, clicker sur le boutton **Créer**
* Pour effectuer une modification, clicker sur **Modifier** depuis la page Menu. Après avoir saisi vos corrections clicker sur **Mettre à jour**. Si vous n'avez aucune modifications à valider, il faut clicker sur **Retour** pour revenir au Menu.
