# ML-F1
Dépôt pour les **cours de Machine Learning (apprentissage automatique)**, classe de terminale spécialité **Sciences de l'ingénieur** du lycée François 1er à Fontainebleau.    
(En cours de développement, les liens pour télécharger les **vidéos et présentations** des cours sont ajoutés régulièrement)  

Le cours utilise beaucoup d'activités pratiques sous Python. Il y a cependant quelques aspects théoriques mathématiques qui sont développés. Ceux qui peuvent éventuellement poser problème à des élèves de Terminales sont :  
* Des notions sur les matrices (Chapitre 4 sur la régression linéaire)
* Des notions de dérivées (l'algorithme du gradient au chapitre 3)
* Des notions sur les probabilités conditionnelles (chapitre 8 sur la méthode de la prolongation lexicale - mais elles sont très succintes il n'y a pas de calcul).  
* Le chapitre 3.i : "Théorie sur l'algorithme du gradient" est quant à lui vraiment hors programme (notions de dérivées partielles et de dérivées de compositions de fonctions). Il permet de comprendre comment est construit l'algorithme de rétropropagation du gradient utlisé dans l'algorithme python. 

Certaines parties peuvent également être étudiées avec des secondes en SNT. Quelques idées :  
* Dans le cadre d'un travail sur les images : Chapitre 6, en particulier l'activité de reconnaissance de police manuscrite, avec transformation des images couleurs en images N&B
* Dans le cadre d'un travail sur le traitement des données : L'ensemble du chapitre 7.  
* Dans le cadre du WEB : Le chapitre 8 (à venir) explique comment les moteurs de recherche mettent en oeuvre des algorithmes de prolongation lexicales pour contextualiser les saisies des utilisateurs. Des vecteurs pré-entrainés en Anglais utilisés dans les réseaux de neurones à convolution 1D sont disponibles sur le site [GolVe](https://nlp.stanford.edu/projects/glove/). On peut trouver des vecteurs pré-entrainés en Français [sur ce site](http://www.cs.cmu.edu/~afm/projects/multilingual_embeddings.html)  
* Toujours dans le cadre du big-data, le chapitre 8 (à venir) peut également servir comme base pour faire un projet avec les élèves sur le thème du "fake news", en utilsant une base de données disponnible sur [le site du gouvernement](https://www.data.gouv.fr/fr/datasets/credibility-corpus-with-several-datasets-twitter-web-database-in-french-and-english) qui a pour but d'analyser l'information dans le cadre des réseaux sociaux par exemple.  

alexandre-antoi.bourrieau[at]ac-creteil.fr


Sommaire du cours :
===================

**1. Environnement de développement Google Colab**  
[(Télécharger ce chapitre - 145Mo)](https://drive.google.com/file/d/1Alm3oPnQvcYEyZinD2uWKDW-63ydW8Dc/view?usp=sharing)     
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;a. [Les carnets Jupyter](http://62.210.208.36/MachineLearning/1.%20Environnement%20de%20d%c3%a9veloppement/2.%20Carnets%20Jupyter%20(Published)/)  
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;b. [Partager ses carnets avec Github](http://62.210.208.36/MachineLearning/1.%20Environnement%20de%20d%c3%a9veloppement/3.%20Partager%20ses%20carnets%20(Published)/)  
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;c. [Quelques définitions](http://62.210.208.36/MachineLearning/1.%20Environnement%20de%20d%c3%a9veloppement/4.%20D%c3%a9finitions%20(Published)/)    
    
**2. Quelques rappels de Python**  
[(Télécharger ce chapitre - 516 Mo)](https://drive.google.com/file/d/1tO5U2Nr3gyd6xmXkIAKO2AhTYQR47VRA/view?usp=sharing)    
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;a. [Syntaxe](http://62.210.208.36/MachineLearning/2.%20Rappels%20de%20Python/2.%20Syntaxe%20(Published)/)  
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;b. [Exercice 1 : Produit scalaire](http://62.210.208.36/MachineLearning/2.%20Rappels%20de%20Python/3.%20Exercice%201%20-%20Produit%20Scalaire%20(Published)/)  
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;c. [Exercice 2 : Tracés de fonctions](http://62.210.208.36/MachineLearning/2.%20Rappels%20de%20Python/4.%20Exercice%202%20-%20Trac%c3%a9s%20de%20fonctions%20(Published)/)  
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;d. [Gestion d'un mot de passe](http://62.210.208.36/MachineLearning/2.%20Rappels%20de%20Python/5.%20Mot%20de%20passe%20(Published)/)    
    
**3. Régression logistique : Structure de base d'un réseau de neurones, Algorithme du gradient et rétropopagation du gradient - Application à la classification d'objets**  
[(Télécharger ce chapitre - 1 Go)](https://drive.google.com/file/d/1Atheylw5oV9irnfuT8h2Fj9CV0JDcTN0/view?usp=sharing)    
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;a. [Présentation du projet](http://62.210.208.36/MachineLearning/3.%20Regression%20logistique/1.%20Pr%c3%a9sentation%20(Published)/), [Les étapes de l'apprentissage automatique](http://62.210.208.36/MachineLearning/3.%20Regression%20logistique/2.%20Etapes%20ML%20(Published)/)  
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;b. [Analyse des données](http://62.210.208.36/MachineLearning/3.%20Regression%20logistique/3.%20Analyse%20des%20donn%c3%a9es%20(Published)/)  
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;c. [Exercice 1 : Distribution des pétales des iris](http://62.210.208.36/MachineLearning/3.%20Regression%20logistique/4.%20Exercice%201%20-%20Distribution%20des%20p%c3%a9tales%20(Published)/)  
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;d. [Modèle de régression logistique](http://62.210.208.36/MachineLearning/3.%20Regression%20logistique/5.%20Mod%c3%a8le%20de%20regression%20logistique%20(Published)/)  
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;e. [Fonction Sigmoïde](http://62.210.208.36/MachineLearning/3.%20Regression%20logistique/6.%20Fonction%20Sigmoide%20(Published)/)  
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;f. [Fonction d'objectifs et de coût](http://62.210.208.36/MachineLearning/3.%20Regression%20logistique/7.%20Fonction%20de%20Perte%20et%20de%20Co%c3%bbt%20(Published)/)  
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;g. [Algorithme du gradient](http://62.210.208.36/MachineLearning/3.%20Regression%20logistique/8.%20Algorithme%20du%20gradient%20(Published)/)  
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;h. [Exercice 2 : Algorithme du gradient](http://62.210.208.36/MachineLearning/3.%20Regression%20logistique/9.%20Exercice%202%20-%20Algorithme%20du%20gradient%20(Published)/)  
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;i. [Théorie de l'algorithme du gradient](http://62.210.208.36/MachineLearning/3.%20Regression%20logistique/10.Th%c3%a9orie_Algo_R%c3%a9tropropagation/)  
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;j. [Rétropropagation du gradient](http://62.210.208.36/MachineLearning/3.%20Regression%20logistique/11.%20R%c3%a9tropropagation_Gradient%20(Published)/)  
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;k. [Entrainement du modèle](http://62.210.208.36/MachineLearning/3.%20Regression%20logistique/12.%20Entrainement%20du%20mod%c3%a8le%20(Published)/)  
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;l. [Exercice 3 : Entrainement du modèle](http://62.210.208.36/MachineLearning/3.%20Regression%20logistique/13.%20Exercice%203%20-%20Entrainement%20du%20mod%c3%a8le%20(Published)/)  
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;m. [Prédictions](http://62.210.208.36/MachineLearning/3.%20Regression%20logistique/14.%20Pr%c3%a9dictions%20(Published)/)  
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;n. [Données d'entrainements et de tests](http://62.210.208.36/MachineLearning/3.%20Regression%20logistique/15.%20Donn%c3%a9es%20d'entrainement%20et%20de%20test%20(Published)/)  
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;o. [Accélérer l'entrainement](http://62.210.208.36/MachineLearning/3.%20Regression%20logistique/16.%20Acc%c3%a9l%c3%a9rer%20l'entrainement%20(Published)/)  
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;p. [Améliorer le modèle](http://62.210.208.36/MachineLearning/3.%20Regression%20logistique/17.%20Am%c3%a9liorer%20le%20mod%c3%a8le%20(Published)/)    
    
**4. Utilisation de la librairie NumPy : Régression linéaire d'odre 1 et 2, travailler avec des images**  
[(Télécharger ce chapitre - 501Mo)](https://drive.google.com/file/d/1APeOguKoQjFTVJ_4plRjAWsMerVenP-A/view?usp=sharing)    
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;a. [Présentation de la librairie](http://62.210.208.36/MachineLearning/4.%20NumPy/1.%20Pr%c3%a9sentation%20(Published)/)  
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;b. [Création de données](http://62.210.208.36/MachineLearning/4.%20NumPy/2.%20Cr%c3%a9er%20des%20donn%c3%a9es%20avec%20NumPy%20(Published)/)  
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;c. [Opérations sur les tableaux](http://62.210.208.36/MachineLearning/4.%20NumPy/3.%20Op%c3%a9rations%20de%20base%20sur%20les%20tableaux%20-%20Copie%20(Published)/)  
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;d. [Régression linéaire](http://62.210.208.36/MachineLearning/4.%20NumPy/4.%20R%c3%a9gr%c3%a9ssion%20lin%c3%a9aire%20(Published)/)  
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;e. [Exemple de régression linéaire](http://62.210.208.36/MachineLearning/4.%20NumPy/5.%20Exemple%20de%20r%c3%a9gr%c3%a9ssion%20lin%c3%a9aire%20(Published)/)  
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;f. [Exercice sur la régression linéaire](http://62.210.208.36/MachineLearning/4.%20NumPy/6.%20Exercice%20de%20r%c3%a9gr%c3%a9ssion%20lin%c3%a9aire%20(Published)/)  
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;g. [Un exemple plus évolué](http://62.210.208.36/MachineLearning/4.%20NumPy/7.%20Un%20exemple%20plus%20%c3%a9volu%c3%a9%20(Published)/)  
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;h. [Fonctions statistiques avec NumPy](http://62.210.208.36/MachineLearning/4.%20NumPy/8.%20Fonctions%20statistiques%20avec%20NumPy%20(Published)/)  
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;i. [Algèbre linéaire avec NumPy](http://62.210.208.36/MachineLearning/4.%20NumPy/9.%20Alg%c3%a8bre%20lin%c3%a9aire%20avec%20NumPy%20(Published)/)  
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;j. [Visualiser des données](http://62.210.208.36/MachineLearning/4.%20NumPy/10.%20Visualiser%20des%20donn%c3%a9es%20(Published)/)  
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;l. [Travailler avec des images](http://62.210.208.36/MachineLearning/4.%20NumPy/11.%20Travailler%20avec%20des%20images%20(Published)/)  
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;m. [Transformer les données](http://62.210.208.36/MachineLearning/4.%20NumPy/12.%20Transformer%20les%20donn%c3%a9es%20(Published)/)    

**5. Utilisation des librairies Keras et Tensorflow : Construction et mise en oeuvre d'un réseau de neurones multi-couches profond (fully connected multi-layer neural network) -  Application à l'approximation de fonctions**  
[(Télécharger ce chapitre - 279 Mo)](https://drive.google.com/file/d/1Gu251mTrDAx-N7_aCZfLqXPrOpCYBszu/view?usp=sharing)    
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;a. [Présentation du projet](http://62.210.208.36/MachineLearning/5.%20Tensorflow/1.%20Pr%c3%a9sentation%20(Published)/)  
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;b. [Vocabulaire utilisé par la librairie Keras](http://62.210.208.36/MachineLearning/5.%20Tensorflow/2.%20Vocabulaire%20Keras%20(Published)/)  
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;c. [Exemple d'un modèle : Réseau de neurones](http://62.210.208.36/MachineLearning/5.%20Tensorflow/3.%20Exemple%20de%20mod%c3%a8le%20(Published)/)  
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;d. [Couches des réseaux de neurones](http://62.210.208.36/MachineLearning/5.%20Tensorflow/4.%20Couches%20des%20mod%c3%a8les%20(Published)/)  
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;e. [Les fonctions d'activations](http://62.210.208.36/MachineLearning/5.%20Tensorflow/5.%20Fonctions%20d'activation%20(Published)/)  
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;f. [Entrainement du modèle](http://62.210.208.36/MachineLearning/5.%20Tensorflow/6.%20Entrainement%20du%20mod%c3%a8le%20(Published)/)  
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;g. [Les fonctions d'objectifs](http://62.210.208.36/MachineLearning/5.%20Tensorflow/7.%20Les%20fonctions%20d'objectif%20(Published)/)  
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;h. [Les optimiseurs](http://62.210.208.36/MachineLearning/5.%20Tensorflow/8.%20Les%20optimiseurs%20(Published)/)  
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;i. [Exemple de prédictions](http://62.210.208.36/MachineLearning/5.%20Tensorflow/9.%20Exemple%20de%20pr%c3%a9dictions%20(Published)/)  
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;j. [Sauvegarde et restauration du modèle](http://62.210.208.36/MachineLearning/5.%20Tensorflow/10.%20Sauvegarde%20et%20restauration%20du%20mod%c3%a8le%20(Published)/)    
    
**6. Construction et mise en oeuvre d'un réseau de neurones à convolution 2D (convolutional neural network) - Application à la reconnaissance d'image :**   
[(Télécharger ce chapitre - 751 Mo)](https://drive.google.com/file/d/11eOwGIXP_nnMszCH4xhcMrqR9iNIbWUq/view?usp=sharing)  
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;a. [Présentation du projet](http://62.210.208.36/MachineLearning/6.%20Exemple%20-%20Reconnaissance%20d'image/1.%20Pr%c3%a9sentation%20(Published)/)  
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;b. [Réseau de neurones à convolution](http://62.210.208.36/MachineLearning/6.%20Exemple%20-%20Reconnaissance%20d'image/2.%20R%c3%a9seaux%20%c3%a0%20convolution%20(Published)/)  
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;c. [Analyse des données](http://62.210.208.36/MachineLearning/6.%20Exemple%20-%20Reconnaissance%20d'image/3.%20Analyse%20des%20donn%c3%a9es%20(Published)/)  
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;d. [Préparation des données](http://62.210.208.36/MachineLearning/6.%20Exemple%20-%20Reconnaissance%20d'image/4.%20Pr%c3%a9paration%20des%20donn%c3%a9es%20(Published)/)  
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;e. [Définition du modèle - Réseau de neurones à convolution](http://62.210.208.36/MachineLearning/6.%20Exemple%20-%20Reconnaissance%20d'image/5.%20D%c3%a9finition%20du%20mod%c3%a8le%20(Published)/)  
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;f. [Entrainement du modèle](http://62.210.208.36/MachineLearning/6.%20Exemple%20-%20Reconnaissance%20d'image/6.%20Entrainement%20du%20mod%c3%a8le%20(Published)/)  
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;g. [Prédictions](http://62.210.208.36/MachineLearning/6.%20Exemple%20-%20Reconnaissance%20d'image/7.%20Pr%c3%a9dictions%20(Published)/)  
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;h. [Analyse des erreurs](http://62.210.208.36/MachineLearning/6.%20Exemple%20-%20Reconnaissance%20d'image/8.%20Analyse%20des%20erreurs%20(Published)/)  
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;i. [Optimisation des hyper-paramètres](http://62.210.208.36/MachineLearning/6.%20Exemple%20-%20Reconnaissance%20d'image/9.%20Optimisation%20des%20hyper-param%c3%a8tres%20(Published)/)  
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;j. [Essais d'optimisation des hyper-paramètres](http://62.210.208.36/MachineLearning/6.%20Exemple%20-%20Reconnaissance%20d'image/10.%20Essais%20d'optimisation%20les%20hyper-param%c3%a8tres%20(Published)/)  
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;k. [Questions fréquentes](http://62.210.208.36/MachineLearning/6.%20Exemple%20-%20Reconnaissance%20d'image/11.%20Questions%20fr%c3%a9quentes%20(Published)/)  
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;l. [Exercice 1 : Test du modèle sur une écriture personnelle](http://62.210.208.36/MachineLearning/6.%20Exemple%20-%20Reconnaissance%20d'image/12.%20Exercice%201%20-%20Test%20du%20mod%c3%a8le%20sur%20une%20%c3%a9criture%20personnelle%20(Published)/)  
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;m. [Exercice 2 : Un autre modèle](http://62.210.208.36/MachineLearning/6.%20Exemple%20-%20Reconnaissance%20d'image/13.%20Exercice%202%20-%20Un%20autre%20mod%c3%a8le%20(Published)/)  
    
**7. Utilisation de la librairie Pandas : Manipuler, transformer et visualiser des données pour le deep-learning**  
[(Télécharger ce chapitre - 338 Mo)](https://drive.google.com/file/d/1DwxPr46uPs1F4OAjLKgpGUcHqvHTH1RM/view?usp=sharing)  
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;a. [Présentation de la librairie Pandas](http://62.210.208.36/MachineLearning/7.%20Pandas/1.%20Pr%c3%a9sentation%20(Published)/)  
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;b. [Où trouver les données ?](http://62.210.208.36/MachineLearning/7.%20Pandas/2.%20O%c3%b9%20trouver%20des%20donn%c3%a9es%20(Published)/)  
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;c. [Chargement et inspection des données](http://62.210.208.36/MachineLearning/7.%20Pandas/3.%20Chargement%20et%20inspection%20des%20donn%c3%a9es%20(Published)/)  
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;d. [Sélection des lignes et des colonnes](http://62.210.208.36/MachineLearning/7.%20Pandas/4.%20S%c3%a9lection%20des%20lignes%20et%20des%20colonnes%20(Published)/)  
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;e. [Inspecter, convertir et trier les données](http://62.210.208.36/MachineLearning/7.%20Pandas/5.%20Inspecter,%20convertir%20et%20trier%20les%20donn%c3%a9es%20(Published)/)  
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;f. [Agrégation de données](http://62.210.208.36/MachineLearning/7.%20Pandas/6.%20Agr%c3%a9gation%20de%20donn%c3%a9es%20(Published)/)  
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;g. [Visualisation de données](http://62.210.208.36/MachineLearning/7.%20Pandas/7.%20Visualisation%20de%20donn%c3%a9es%20(Published)/)  
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;h. [Exercice](http://62.210.208.36/MachineLearning/7.%20Pandas/8.%20Exercice%20(Published)/)    

**8. Recommandations et analyse des ressentis avec GloVe : Mise en place d'un réseau de neurones à convolution 1D pour l'analyse de textes**  
[(Télécharger ce chapitre - 670Mo)](https://drive.google.com/file/d/1yqkEm2Ewj6FuOetdKX-Ary-Ca565v3F1/view?usp=sharing)  
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;a. [Présentation : Qu'est-ce que l'analyse des ressentis ?](http://62.210.208.36/MachineLearning/8.%20Recommandations/1.%20Pr%c3%a9sentation%20(Published)/)  
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;b. [Prolongation lexicale (Word embedding)](http://62.210.208.36/MachineLearning/8.%20Recommandations/2.%20Word%20embedding%20(Published)/)  
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;c. [Chargement et analyse des données utlisées pour l'entrainement et le test de notre modèle](http://62.210.208.36/MachineLearning/8.%20Recommandations/3.%20Chargement%20des%20donn%c3%a9es%20(Published)/)  
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;d. [Chargement des vecteurs GloVe et préparation des données](http://62.210.208.36/MachineLearning/8.%20Recommandations/4.%20Pr%c3%a9paration%20des%20donn%c3%a9es%20(Published)/)  
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;e. [Classification de ressentis à l'aide d'un réseau de neurones à convolution 1D sous Keras](http://62.210.208.36/MachineLearning/8.%20Recommandations/5.%20D%c3%a9finition%20du%20mod%c3%a8le%20(Published)/)  
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;f. [Entrainement, prédictions et analyse des erreurs du modèle](http://62.210.208.36/MachineLearning/8.%20Recommandations/6.%20Entrainement%20du%20mod%c3%a8le,%20pr%c3%a9dictions%20et%20analyse%20des%20erreurs%20(Published)/)  
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;g. [Quelques modèles utilisés pour le traitement naturel du langage (BERT, RoBERTa, CamemBERT)](http://62.210.208.36/MachineLearning/8.%20Recommandations/7.%20Quelques%20mod%c3%a8les%20utilis%c3%a9s%20dans%20le%20traitement%20naturel%20du%20langage%20(Published)/)  
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;h. [Exemple de CamemBERT : Prédiction de mots "masqués" dans un texte](http://62.210.208.36/MachineLearning/8.%20Recommandations/8.%20Exemple%20d'utilisation%20de%20CamemBERT%20(Published)/)  
      
**9. Principe de fonctionnement de BERT**  
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;a. Présentation  
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;b. [Les réseaux de neurones récurrents](http://62.210.208.36/MachineLearning/9.%20Principe%20de%20fonctionnement%20de%20BERT/2.%20Les%20r%c3%a9seaux%20de%20neurones%20r%c3%a9currents%20(Published)/)  
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;c. [Le concept d'attention](http://62.210.208.36/MachineLearning/9.%20Principe%20de%20fonctionnement%20de%20BERT/3.%20Le%20concept%20d'attention%20(Published)/)  
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;d. Le modèle "Transformer"
    
    
    

  
