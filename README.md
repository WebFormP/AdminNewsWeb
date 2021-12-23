# AdminNewsWeb
Interface d'administration de NewsWeb, réalisée avec Bootstrap 5

Pour permettre la gestion du site NewsWeb via un CRUD, on doit disposer de pages pour créer/lire/modifier/supprimer les articles.
Ces pages seront écrites simplement en HTML/CSS et devront être transformées plus tard en PHP.

## Pages

Accueil (tableau de bord)		=> index.html

Créer un article => creerArticle.html
Lire les articles => lireTousArticles.html
Lire un article =>lireArticle.html
Modifier un article	=> modifierArticle.html
Supprimer un article	=> supprimerArticle.html

Connexion/déconnexion (login/logout)	=> login.html

## Description d'un article

Un article est composé de :
- Titre
- Date et heure (généré automatiquement à la création)
- Nom de l'auteur
- Contenu (texte, images, vidéos,...)
- Résumé (extrait du contenu généré automatiquement, modifiable)
- Catégorie(s) de l'article
- Image mise en avant

NB: l'interface Front-End, voir le repository NewsWeb, doit être complétée pour tenir compte des catégories.
