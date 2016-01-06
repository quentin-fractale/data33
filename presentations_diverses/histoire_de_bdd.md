# Vous avez dit BDD ?

- **Niveau** : **Débutant** / Intermédiaire / Avancé / Expert
- **Auteur** : Vincent Bergeot
- **Date de MàJ** : 06/01/2016
- **Licence** : CC-by-sa

## Objectifs de cette présentation
Découvrir les bases de données :

- Définition
- Quelques abréviations
- Quelques ordres de grandeurs
- Contruire une base de données

## Définition
*Une base de données (en anglais : database) est un outil permettant de stocker et de retrouver l'intégralité de données brutes ou d'informations en rapport avec un thème ou une activité ; celles-ci peuvent être de natures différentes et plus ou moins reliées entre elles. Dans la très grande majorité des cas, ces informations sont très structurées, et la base est localisée dans un même lieu et sur un même support.*

https://fr.wikipedia.org/wiki/Base_de_donn%C3%A9es

## Différence entre tableur et base de données

Pour faire cette table ![](https://raw.githubusercontent.com/vinber/data33/master/presentations_diverses/img/bdd-01.png)

#### Dans un tableur
je note les noms de colonnes, je remplis les données.

**Problème : j'écris trois fois Durand**

Alors que je pourrai n'écrire que cela :

![](https://raw.githubusercontent.com/vinber/data33/master/presentations_diverses/img/bdd-02.png)

Mais dans ce cas, j'ai besoin de connaître la "relation" entre "Durand" d'une part et "Paul, Jacques, Louis"

#### Dans une base de données
Je vais créer 2 tables 
![](https://raw.githubusercontent.com/vinber/data33/master/presentations_diverses/img/bdd-03.png)

et définir une relation entre elles ![](https://raw.githubusercontent.com/vinber/data33/master/presentations_diverses/img/bdd-04.png)

Pour obtenir à la fin une base de données avec plusieurs tables :

![](https://raw.githubusercontent.com/vinber/data33/master/presentations_diverses/img/bdd-05.png)

Donc effectivement pour 3 enfants et leur père ce n'est pas forcément nécessaire mais si on fait cela pour tous les pères du monde !!!

#### Conclusion
Pour peu de données, un tableur est suffisant, facile à mettre en œuvre, utilisation relativement simple, permet de rapidement voir si les données sont *propres* (en triant, observant, ...)

Pour beaucoup de données, la base de données devient nécessaire. Plus performante sur des gros volume de données, plus adaptées pour faire des recherches et des vérifications de "propreté", la mise en œuvre demande une plus grande réflexion sur les tables de données et leurs relations.

## Quelques abréviations
- bdd -> Base de données
- sgbd -> Système de Gestion de Base de Données
 - l'ensemble des logiciels qui vont permettre d'exploiter la base de données
- ODbL -> Open Database License
 - licence permettant la réutilisation des données contenues dans la base -> fréquemment utilisée pour les données ouvertes.

## Quelques ordres de grandeurs
de quelques mégaoctets à plusieurs téraoctet

## Des données plus ou moins structurées
Dans une base de données "classique "relationnelles, la structure de départ est primordiale et souvent complexe à modifier par la suite.

On parle de plus en plus de base de données NoSQL (Not only SQL en anglais).

## Aller + loin : 
Quelques sources : 

## A savoir : 
Les images proviennent du site http://www.3stone.be, sous licence CC-by-sa

## Cadre d'utilisation
