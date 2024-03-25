# P3-OC-DataScientist

## Projet : Concevez une application au service de la santé publique
Projet 3 de la formation OpenClassrooms du parcours data scientist

## Objectifs du projet
Participation d’un appel à projet lancé par l'agence "Santé publique France" pour trouver des idées innovantes d’applications en lien avec l’alimentation.

L'objectif est de proposer un produit avec un Nutriscore  A ou B à la place d'un produit avec un nutriscore C, D ou E : tout en gardant la même catégorie et avec le même apport en nutriment que le produit demandé 

Bonus : Calculer le Nutrition Grade pour les nouveaux produits rentrés dans la base

### Données à disposition 
Base de données de produits alimentaires ouverte et collaborative composée de plus de 320 000 produits et 162 variables

Variables disponibles :
- Informations générales sur le produit : le code du produit, l’url, le nom du produit, la quantité, la date de modification…
- Des tags : catégorie du produit, marque, l’origine du produit, le magasin où on peut acheter le produit, les pays où on peut trouver le produit..
- Les ingrédients composant le produit et les potentiels additifs
- Des informations nutritionnelles : quantité en grammes d’un nutriment (en g ou kJ) pour 100 grammes du produit : l'énergie, le sel, le sucre, le gras…
- Le Nutriscore : repère graphique qui classe les produits selon un score prenant en compte la teneur en nutriment et aliments à favoriser et ceux à limiter : A (« meilleure qualité nutritionnelle ») à E (« moins bonne qualité nutritionnelle »).

### Missions 

1) Traiter le jeu de données, en :
- Réfléchissant à une idée d’application.
- Repérant des variables pertinentes pour les traitements à venir, et nécessaires pour votre idée d’application.
- Nettoyant les données en :
  - mettant en évidence les éventuelles valeurs manquantes, avec au moins 3 méthodes de traitement adaptées aux variables concernées,
  - identifiant et en quantifiant les éventuelles valeurs aberrantes de chaque variable.
- Automatisant ces traitements pour éviter de répéter ces opérations

2) Tout au long de l’analyse, produire des visualisations afin de mieux comprendre les données. Effectuer une analyse univariée pour chaque variable intéressante, afin de synthétiser son comportement.

3) Confirmer ou infirmer les hypothèses à l’aide d’une analyse multivariée. Effectuer les tests statistiques appropriés pour vérifier la significativité des résultats.
  
4) Justifier votre idée d’application. Identifier des arguments justifiant la faisabilité (ou non) de l’application à partir des données Open Food Facts.

5) Rédiger un rapport d’exploration et pitcher votre idée durant la soutenance du projet.

## Compétences évaluées
- Communiquer ses résultats à l’aide de représentations graphiques lisibles et pertinentes
- Effectuer des opérations de nettoyage sur des données structurées
- Effectuer une analyse statistique multivariée
- Effectuer une analyse statistique univariée

## Découpage des dossiers

- Saubot_Julie_1_notebook_nettoyage_112022.ipynb : notebook comportant le nettoyage des données 
- Saubot_Julie_2_notebook_exploration_112022.ipynb : notebook comportant les analyses exploratoires réalisées : une analyse univariée, multivariée, une réduction dimensionnelle, ainsi que les différentes questions de recherches associées
- Saubot_Julie_3_presentation_112022.pptx : support de présentation pour la soutenance
  
## Lien utiles

- Données utilisées : https://world.openfoodfacts.org
- Explication des variables : https://world.openfoodfacts.org/data/data-fields.txt
