# Cheat Sheet Exploration de Données

Ce projet contient un script Python illustrant une approche pour l'exploration de données. Le script montre comment importer des modules, lire un fichier CSV, décrire et prétraiter les données, et enfin visualiser les résultats à l'aide de bibliothèques populaires telles que pandas, numpy, matplotlib et seaborn.

## Contenu du projet

- **script.py** : Le script Python contenant toutes les étapes de l'exploration de données.
- **data.csv** : Exemple de fichier CSV à analyser (à fournir ou modifier selon vos besoins).
- **output.csv** : Fichier CSV exporté après transformation (généré par le script).

## Fonctionnalités

Le script se décompose en plusieurs parties :

1. **Import des modules nécessaires**  
   Importation de bibliothèques Python essentielles pour la manipulation et la visualisation des données.

2. **Lecture du fichier CSV**  
   Chargement du fichier CSV dans un DataFrame pandas.

3. **Description des données**  
   - Affichage des colonnes et de la dimensionnalité du DataFrame.
   - Statistiques descriptives sur les variables.
   - Informations sur les types de données et détection des valeurs manquantes (nombre et pourcentage).
   - Comptage des valeurs uniques et identification de la valeur la plus fréquente (mode).

4. **Preprocessing et transformation**  
   - Conversion de colonnes de dates en format datetime et modification du format de la date.
   - Remplissage des valeurs manquantes.
   - Conversion des types de données et remplacement des valeurs spécifiques.
   - Agrégation avec la méthode groupby et filtrage des lignes et colonnes.
   - Exportation du DataFrame transformé vers un fichier CSV.

5. **Visualisation des données**  
   - Visualisation basique avec la méthode `plot` de pandas.
   - Création de graphiques plus avancés avec Seaborn et Matplotlib.
   - Réalisation d'un nuage de points (scatterplot) et d'une heatmap pour l'analyse des corrélations.

## Prérequis

- **Python 3.x**

Les bibliothèques suivantes doivent être installées :

- pandas
- numpy
- matplotlib
- seaborn

Vous pouvez les installer en exécutant :

```bash
pip install pandas numpy matplotlib seaborn

