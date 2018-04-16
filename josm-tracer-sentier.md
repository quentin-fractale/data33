# Tracer un sentier dans OSM

- **Niveau** : Débutant / Intermédiaire / **Avancé** / Expert
- **Auteur** : Vincent Bergeot
- **Date de MàJ** : 09/03/2018
- **Licence** : CC-BY-SA

## Principes - Ce que nous allons faire

- Construire un itinéraire pédestre avec JOSM pour contribuer à OpenStreetMap


## Ingrédients - Ce dont nous avons besoin

- [JOSM](https://josm.openstreetmap.de/)
- la connaissance de l'itinéraire (une personne, une trace gps, un tracé , ...)

! **Attention** : s'assurer d'avoir les droits pour tracer l'itinéraire. Le plus simple, le faire avec "l'opérateur". Dans le cas des itinéraires de la fédération française de randonénes pédestres, l'utilisation est proscrite MAIS en discussion !!!

## Étapes - Comment allons-nous procéder ?

- Dans josm, mettre un fond osm et un fond "photos",
    - menu Imagerie
- OPTION créer un calque (ctrl+N)
    - pour dessiner l'itinéraire
    - ou y importer une trace gpx
    - clic-droit sur le calque pour "dissuader l'envoi"
- Récupérer les données dans un **nouveau calque** sur la zone de l'itinéraire,
- créer la relation correspondante à l'itinéraire :
    - aller dans préréglages/relations/itinéraires/itinéraires de randonnées pédestres
    - une fenêtre s'ouvre (en cliquant sur l'épingle bleue en haut à droite, cela l'ajoute à la barre d'outils)
    - renseigner les champs Nom, Réseau, Référence, Société, Distance, dénivellé, Aller-Retour)
- Ajouter les éléments dans la relation
    - en se servant des éléments déjà présents et en coupant les routes, sentiers, pistes utilisés par l'itinéraire (le raccourci P est votre ami pour couper les chemins),
- Quand l'ensemble de l'itinéraire se trouve dans la relation on vérifie puis on envoie les données,

## Aller + loin : 
Quelques sources :

- Cartographier un [panneau de guidage](https://wiki.openstreetmap.org/wiki/FR:Tag:information%3Dguidepost) avec tourism=information et information=guidepost, role
- [page wiki en français sur les itinéraires](https://wiki.openstreetmap.org/wiki/FR:Relation:route)
- [page wiki en anglais sur les itinéraires de randonnées](https://wiki.openstreetmap.org/wiki/Tag:route%3Dhiking) *à traduire*

## A savoir : 

- Un itinéraire (route en anglais) est un parcours pré-déterminé et connu du public,
- Un itinéraire dans OpenStreetMap est une [relation](https://wiki.openstreetmap.org/wiki/FR:Relations), regroupant différents objets (points et chemins),
- quelques extensions à JOSM / route, geojson

## Liens avec d’autres fiches : 

