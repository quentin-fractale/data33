# Intégrer un calque distant Umap dans une carte Umap

- **Niveau** : Débutant / Intermédiaire / **Avancé** / Expert

- **Auteur** : Vincent Bergeot, avec l'aide d'un échange sur le forum OpenStreetMap

## Principes - Ce que nous allons faire

- À partir d'une carte Umap1, comportant plusieurs calques, nous allons extraire "l'adresse" d'un seul calque pour l'intégrer dans une calque Umap2


## Ingrédients - Ce dont nous avons besoin

- 2 cartes Umap


## Étapes - Comment allons-nous procéder ?

- Sur la carte Umap 1 masquer tous les calques qui ne nous intéresse pas,
- Cliquer sur "exporter et partager la carte", Choisir Options d'export de l'iframe", cliquer sur "Garder les calques visibles actuellement"
- Dans le code généré au dessus, chercher l'identifiant faisant suite à ...&datalayers=<id calque>
- Dans la carte Umap2, créer un nouveau calque, renseigner dans Données Distantes l'URL du calque souhaité "http://umap.openstreetmap.fr/fr/datalayer/<id carte>/<id calque>/ et choisir geojson comme format de données.
- Enregistrer


Dans votre carte Umap2, les données du calque choisi dans la carte Umap1 vont apparaitre.


Il semble qu'il existe un bug qui fait que lorsque vous êtes en mode d'édition dans Umap, vous puissiez ne pas voir le calque distant, il est cependant visible quand vous vous déconnectez (pensez parfois à recharger la carte, Ctrl+R ou F5)
