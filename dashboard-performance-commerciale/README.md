# Dashboard Power BI : Performance commerciale

Rapport interactif de **3 pages** construit sur le dataset [Sample Superstore](https://www.kaggle.com/datasets) : **9 994 transactions retail** (ventes, profit, quantités, remises) sur 4 régions, 3 segments clients et 17 sous-catégories de produits.

## Architecture

- **Modèle en étoile** : table de faits `Faits_Ventes` + 3 tables de dimension (`Dim_Région`, `Dim_Produit`, `Dim_Segment`)
- **6 mesures DAX** : CA total, profit total, marge %, quantité vendue, remise moyenne, nombre de transactions
- **Slicers croisés** : région, segment client, catégorie de produits

## Les 3 pages

1. **Vue d'ensemble** : 4 cartes KPI, CA par région, répartition par segment
2. **Analyse produit** : ventes et profit par sous-catégorie, matrice de rentabilité catégorie × région avec mise en forme conditionnelle
3. **Performance régionale** : carte géographique, tableau récapitulatif, répartition du profit

## Enseignements clés

- **Écart de marge régional majeur** : 14,94 % (West) contre 7,92 % (Central) : la région Central génère du volume mais détruit de la marge
- **Sous-catégories à profit négatif** : Tables et Bookcases perdent de l'argent dans toutes les régions
- **Furniture** est la catégorie la moins rentable partout (marge globale 2,49 % vs 17,4 % pour Technology)

Le rapport permet à un décideur d'identifier en moins de deux minutes les zones et produits nécessitant une action corrective : sans analyse manuelle.

## Fichiers

- `Dashboard_Performance_Commerciale.pbix` : fichier source Power BI
- `Dashboard_Performance_Commerciale.pdf` : export PDF des 3 pages
