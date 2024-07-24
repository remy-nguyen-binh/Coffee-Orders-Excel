## Aperçu du projet 
Ce projet vise à fournir des insights sur les tendances de vente, en se concentrant sur les différents types de café, la répartition géographique, les principaux clients et l'utilisation des cartes de fidélité.

Au cours de ces quatre années, nous examinerons les performances mensuelles et annuelles des ventes, identifierons les catégories de café populaires, et évaluerons les ventes dans divers pays pour repérer les marchés clés et les opportunités émergentes.

De plus, nous profilerons les cinq principaux clients en fonction du volume d'achat, analyserons leurs comportements d'achat, et évaluerons l'impact de notre programme de carte de fidélité sur les ventes et la fidélisation des clients. Grâce à cette analyse, nous visons à identifier les zones de croissance potentielles, à optimiser notre offre de produits, et à développer des stratégies de marketing ciblées pour améliorer l'engagement des clients et réussir notre activité.

## Source des données
Vous pouvez télécharger le fichier Excel  [ici](https://github.com/mochen862/excel-project-coffee-sales).

## Outils
Excel pour nettoyer et transformer les données, puis analyse avec des tableaux croisés dynamiques et création d'un tableau de bord.

## Nettoyage des données
### Collecte des données
J'ai utilisé XLOOKUP pour faire correspondre les ID des clients entre les tables Clients et Commandes, ajoutant les adresses e-mail des clients.

J'ai connecté les ID des produits de la table Commandes à la table Produits en utilisant XLOOKUP, récupérant des détails tels que le Type de café, la Taille, le Type de torréfaction et le Prix unitaire.

### Transformation des données
Après avoir collecté et connecté les données des tables Commandes, Clients et Produits, l'étape suivante est de transformer les données pour une meilleure clarté et analyse. Une transformation essentielle est la normalisation des noms des types de café. En convertissant les abréviations en leurs noms complets, nous pouvons garantir la cohérence et améliorer la lisibilité.

### Formatage des données
J'ai formaté les données pour plus de clarté et de cohérence pour nos parties prenantes asiatiques. J'ai modifié le format des dates en jour/mois/année, ajouté "kg" aux valeurs de taille, et ajouté le symbole "$" aux prix unitaires. J'ai supprimé les doublons, transformé les cellules vides en "N/A", et converti l'ensemble des données en tableau pour une gestion et une analyse plus faciles.

## Analyse des données
J'ai créé des tableaux croisés dynamiques pour obtenir une vue d'ensemble des données de commandes de café, puis construit un tableau de bord Excel.

## Recommandations
1- Concentrer les efforts sur les pays avec les meilleures ventes** : Diriger les efforts de marketing vers les pays avec de fortes ventes.
2- Optimiser la sélection des produits** : Adapter l'offre de produits en fonction des articles populaires pour répondre efficacement à la demande des clients.
3- Personnaliser l'engagement client** : Utiliser les insights des principaux clients pour adapter les programmes de marketing et de fidélité pour un meilleur engagement.
4- Encourager l'utilisation des cartes de fidélité** : Promouvoir l'adoption des cartes de fidélité pour augmenter la fidélisation des clients et les achats répétés.
5- Etre agile** : Surveiller en continu les tendances de vente et adapter les stratégies en conséquence pour rester compétitif sur le marché.
