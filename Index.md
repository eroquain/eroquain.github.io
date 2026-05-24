---
title: Cours fondamentaux S1
subtitle:


# Summary for listings and search engines
summary:  Apprentissage statistique, Modèle linéaire et grande dimension, Estimation non-paramétrique, Introduction à l’apprentissage automatique, Optimisation convexe séquentielle et applications



# Date published
date:  

# Date updated
lastmod:  "2022-07-06"

# Is this an unpublished draft?
draft: false

# Show this page in the Featured widget?
featured: false

weight: 20


---
- 5 cours obligatoires en machine learning, statistique mathématique et optimisation
- de septembre à décembre
- examens après la toussaint et début janvier
- rattrapages en juin
- 30 ECTS
- plateforme pédagogique :  [**Moodle**](https://moodle-sciences-24.sorbonne-universite.fr/)

|Intitulé de cours|Enseignant·e·s|
|---|---|   
|[Apprentissage statistique](#apprentissage-statistique)|G. Biau|
|[Estimation non-paramétrique](#estimation-non-paramétrique)|I. Castillo & C. Dion|
|[Introduction à l’apprentissage automatique](#introduction-à-l-apprentissage-automatique)|M. Sangnier|
|[Modèle linéaire et grande dimension](#modèle-linéaire-et-grande-dimension)|E. Roquain|
|[Optimisation pour l'apprentissage automatique](#optimisation-pour-l-apprentissage-automatique)|R. Berthier|


### Apprentissage statistique

**Responsable**  [G. Biau](https://perso.lpsm.paris/~biau/)   

**Objectif**  Ce cours présente les grands principes de l'apprentissage statistique et les problématiques liées.

**Prérequis**  Notions fondamentales de probabilités et statistique.

**Thèmes abordés**

1. Introduction au problème de la classification supervisée
2. Principe de minimisation du risque empirique, théorie de Vapnik-Chervonenkis
3. Bornes de performance, pertes convexes, sélection de modèle
4. Classification non paramétrique, théorème de Stone, plus proches voisins, arbres
5. Classification par réseaux neuronaux
6. Quantification et clustering

### Estimation non-paramétrique

**Responsables**  [I. Castillo](https://perso.lpsm.paris/~castillo/)  & [C. Dion](https://sites.google.com/site/charlottedionblanc/)  

**Objectif**   Présenter des méthodes classiques d'estimation non-paramétrique, étudier le comportement des estimateurs introduits pour différents risques, introduire à l'optimalité des vitesses de convergence au sens minimax. Les notions introduites seront illustrées dans des exemples de modèles statistiques très utilisés en pratique : estimation de densité, régression non-paramétrique, signal en bruit blanc gaussien, modèles de graphes aléatoires.

**Prérequis**  Notions fondamentales de probabilités, bases de statistique, estimation paramétrique, bases d'analyse fonctionnelle (cas Hilbert au moins).

**Thèmes abordés**

1. Estimation non-paramétrique de densité
2. Modèles de bruit blanc, de régression et de convolution
3. Sélection de paramètres
4. Seuillage et estimateurs par ondelettes
5. Modèles de graphes aléatoires
6. Bornes inférieures de vitesses au sens minimax
7. Régions de confiance non-paramétriques   

### Introduction à l' apprentissage automatique

**Responsable**  [M. Sangnier](https://perso.lpsm.paris/~msangnier/index.html)    

**Objectif**   Ce cours introduit les principales méthodes de prédiction (classification et régression), de clustering et de réduction de dimension. Il présente l'apprentissage statistique d'un point de vue algorithmique et sera illustré par des travaux pratiques (en Python) ainsi que par un challenge en science des données.

**Prérequis**  Notions fondamentales de probabilités et statistique, analyse convexe, algèbre linéaire et calcul scientifique en Python.

**Thèmes abordés**

1. Analyse discriminante, régression logistique, machines à vecteurs supports
2. k-plus proches voisins, arbres de décision et méthodes ensemblistes (forêts et boosting)
3. Modèle de mélange et algorithme EM, k-moyennes, clustering spectral et hiérarchique
4. Analyse en composantes principales, projections aléatoires et positionnement multidimensionnel


### Modèle linéaire et grande dimension

**Responsable**  [E. Roquain](http://etienne.roquain.free.fr/)    

**Objectif** appréhender les problématiques issues de la grande dimension dans le
modèle linéaire.  

**Prérequis**  Notions fondamentales de probabilités et statistique, logiciel R.

**Thèmes abordés**

1. Seuillage et hypothèse de parcimonie (sparsité)
2. Estimateurs pénalisés : ridge et LASSO
3. Régression logistique, régression Poisson et modèle linéaire généralisé
4. Sélection et contrôle du taux de faux positifs
5. Prédiction conformelle



### Optimisation pour l' apprentissage automatique


**Responsable**  [R. Berthier](https://raphael-berthier.github.io/)    

**Objectif**   l'objectif de ce cours est de présenter les principales méthodes d'optimisation pour les modèles d'apprentissage ainsi que leurs implications (interpolation, régularisation implicite). On abordera ensuite l'optimisation pour les réseaux de neurones, l'apprentissage en ligne et les bandits. Le cours sera illustré par de séances de TP en Python.

**Prérequis**  Notions fondamentales de probabilités et statistique, calcul scientifique en Python

**Thèmes abordés**

1. Minimisation du risque empirique et erreur de généralisation
2. Méthodes d'optimisation et descente de gradient stochastique
3. Réduction de variance et accélération
4. Interpolation, modèles sur-paramétrés et descente de gradient par coordonnée 
5. Réseaux de neurones et régularisation implicite
6. Apprentissage en ligne et bandits
