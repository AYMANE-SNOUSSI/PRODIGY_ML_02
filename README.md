# PRODIGY_ML_Task02 - Customer Segmentation with K-Means Clustering
#description :
Dans ce projet, nous implémentons un modèle de clustering K-means pour segmenter des clients en différents groupes basés sur leur revenu annuel et leur score de dépense. Le modèle aide à identifier des segments de clientèle pour mieux comprendre le comportement des clients et adapter les stratégies marketing. Ce projet utilise un ensemble de données clients comprenant les attributs : ID, sexe, âge, revenu annuel (k$) et score de dépense (sur une échelle de 1 à 100).
#Objectifs :
-Identifier des groupes de clients similaires selon leur profil financier et leurs habitudes de dépenses.
-Optimiser le nombre de clusters à l'aide de la méthode du coude (Elbow Method) pour choisir la meilleure valeur de K.
-Visualiser les segments de clients pour une meilleure interprétation et compréhension des résultats.
#Contenu :
kmeans_clustering.ipynb : Notebook Jupyter contenant les étapes d'exploration des données, de la sélection du nombre optimal de clusters, et de l'implémentation du modèle K-means.
README.md : Ce fichier, qui explique les objectifs, le contenu et les détails du projet.
#Dataset : 
Le dataset utilisé est constitué de cinq colonnes :
-CustomerID : Identifiant unique de chaque client
-Gender : Sexe du client
-Age : Âge du client
-Annual Income (k$) : Revenu annuel en milliers de dollars
-Spending Score (1-100) : Score de dépense attribué selon le comportement et les habitudes de dépenses
#Resultats :
Le modèle K-means a divisé les clients en 5 groupes, basés sur leurs habitudes de dépenses et leurs revenus. Cette segmentation aide à identifier des profils de clients distincts pour de meilleures décisions stratégiques.
