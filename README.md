# Nom de l'application : Komer

## Cahier des charges :

### Définition du projet : 

    Une entreprise lyonnaise fait appel aux services de votre société de services pour la conception 
d’une application mobile Android à destination du Google Play.
Le cahier des charges vous est fourni et vous avez un délai de 2 mois pour réaliser l’application.

### Fonctionnel (100 points) 

    Les sections suivantes présentent le contenu attendu de l’application. Chaque point doit être 
respecté pour être validé par le client final.

**ATTENTION !** Si certains points ne sont pas clairs ou manquent de détails, c’est à vous de 
contacter le client.

### Inscription utilisateur (10 points) 

    A l’aide de Firebase, il vous est demandé de permettre l’inscription des utilisateurs. Une 
interface devra permettre de saisir les informations de base telles que :
• Le nom d’utilisateur
• Le mot de passe
• La confirmation du mot de passe

### Connexion utilisateur (10 points) 

    Suite à la création d’un compte utilisateur, le client devra pouvoir se connecter au service grâce 
aux identifiants précédemment saisies.

### Rechercher des recettes (10 points) 

    Il s’agira de la page principale de l’application. C’est ici que l’utilisateur va pouvoir faire une 
recherche concernant des recettes de cuisine via un ou plusieurs mots-clés.
Chaque recherche devra afficher a maxima 30 résultats.

**BONUS** 

    Gérer la pagination au sein de la recherche. Une fois arrivée en bas de la liste, la page suivante 
est automatiquement chargée si elle existe.

### Détails des recettes (15 points) 

    La page de détails d’une recette est probablement la plus importante de toute l’application. C’est 
grâce à elle que l’utilisateur va pouvoir consulter toutes les informations relatives à la recette : 
• Le titre
• L’image principale de la recette
• Le temps de préparation
• L’URL source de la recette
• La liste des ingrédients nécessaire à la préparation
• Afficher une image si la recette est pour végan
• Afficher une image si la recette est pour végétarien
• La description
• Proposer la liste des recettes similaires 

### Gestion des favoris (15 points) 

    Afin de faciliter la vie aux utilisateurs, ceux-ci doivent pouvoir sauvegarder en favoris des recettes. 
Ces favoris sont intimement liés au compte de l’utilisateur. De ce fait, si un utilisateur installe 
l’application sur un autre téléphone et qu’il se connecte avec son compte, il doit pouvoir 
récupérer tous ces favoris.
A tout moment, un utilisateur doit pouvoir supprimer une recette de ces favoris. Bien entendu, 
depuis la page des favoris, l’utilisateur doit pouvoir accéder aux détails d’une recette.

### Partager des recettes (5 points) 

    Lorsque vous êtes sur la page d’une recette, l’utilisateur doit pouvoir partager le titre et la 
description d’une recette via d’autres applications.

### Gestion des erreurs (5 points) 

    Lors de la vie de l’application de nombreuses erreurs peuvent survenir. Ces erreurs doivent être 
gérées. En aucun cas l’application Android ne doit cracher. Il sera nécessaire de personnaliser 
l’affichage en fonction des erreurs. 
Par exemple, lors de la connexion, si cette dernière échoue à cause d’une ou plusieurs 
informations incorrectes, il sera valide d’afficher « Information de connexion erronées, merci de 
réessayer » plutôt que « Oups une erreur est survenue ».

### Interface graphique (10 points) 

    L’UI de l’application est laissé à votre jugement. Il va cependant de soi qu’elle doit être utilisable 
et se baser principalement sur Material Design.

### Contraintes techniques (20 points) 

    Le client souhaite reprendre en interne de la société le développement de l’application. De ce fait 
il vous est nécessaire de respecter plusieurs contraintes techniques :
• L’application doit être pour la plateforme Android
• L’application doit être développée avec le langage Kotlin
• Le projet doit utiliser le pattern MVVM
• Utilisation de design pattern
• Respect des principes SOLID

### Outils et aide 

    L’utilisation de librairie externe stable est possible et recommandé. Il vous faut utiliser l’API 
suivante pour le projet : https://spoonacular.com/food-api/docs
Organisation 
Vous composerez une équipe de maximum 2 personnes. Vous ne pourrez pas changer de 
groupe après la composition de celui-ci.


### Rendu 

    Le rendu devra être fait sur un git mis à disposition avant la date limite : 27 mars 2022 avant 23h59.
Les droits de lecture et d’écriture devront être donnés au client.
