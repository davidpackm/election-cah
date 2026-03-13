# Structure des comportements électoraux à la présidentielle française de 2022

## Présentation

Ce projet vise à analyser la structure des résultats de l’élection présidentielle française de 2022 à partir d’une approche statistique en trois temps : description des données, Analyse Factorielle des Correspondances (AFC) et Classification Ascendante Hiérarchique (CAH).

L’objectif est de mettre en évidence les grands clivages électoraux ainsi que des groupes homogènes d’unités d’observation partageant des profils de vote proches.

## Problématique

Au-delà des scores bruts obtenus par les candidats, les données électorales peuvent être analysées comme un espace structuré de proximités, d’oppositions et de regroupements.

Ce projet cherche donc à répondre à plusieurs questions :

- quelles sont les principales lignes de structuration du vote ?
- quelles proximités ou oppositions apparaissent entre profils électoraux ?
- peut-on identifier des groupes homogènes de territoires ou d’unités présentant des comportements similaires ?

## Démarche

### 1. Analyse descriptive
Étude complète du jeu de données pour comprendre la structure du tableau, les distributions observées et les grands contrastes électoraux.

### 2. Analyse Factorielle des Correspondances
Réduction dimensionnelle du tableau afin d’identifier les axes structurant l’espace électoral et d’interpréter les principales oppositions.

### 3. Classification Ascendante Hiérarchique
Construction d’une typologie des unités observées à partir des coordonnées factorielles ou des données normalisées, selon le choix méthodologique retenu.

## Résultats attendus

Le projet permet de produire :
- une lecture descriptive des résultats ;
- un plan factoriel interprétable ;
- un dendrogramme ;
- une partition en clusters ;
- une typologie de profils électoraux.

## Outils
- R
- FactoMineR
- factoextra
- ggplot2
