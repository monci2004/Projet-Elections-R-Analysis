# 🗳️ Analyse Électorale France 2017 (Version R)

![Graphique R ggplot2](plots/dendrogramme-apres-nettoyage-des-donnes.png)
*(dendrogramme CAH apres le nettoyage)*

## 🔗 Lien vers la version Python
> **Note :** Ce projet est l'implémentation **R (Tidyverse)** de l'analyse.
> Une version alternative utilisant **Python & Power BI** est disponible ici :
> 👉 **[Voir le projet Python & Power BI](https://github.com/monci2004/Elections-France-2017-Clustering)**

## 📄 Description
Ce projet explore les dynamiques électorales de 2017 en utilisant la puissance statistique de **R**.
L'objectif est de reproduire une segmentation territoriale (Clustering) et de visualiser les corrélations entre les candidats via des méthodes statistiques avancées.

## 🛠️ Stack Technique (R)
* **Langage :** R 4.x
* **Manipulation de données :** Tidyverse (`dplyr`, `tidyr`, `readr`)
* **Visualisation :** `ggplot2` (Grammar of Graphics), `corrplot`
* **Statistiques / Clustering :** `stats` (kmeans, hclust), `factoextra` (pour la visualisation des clusters)

## 🚀 Fonctionnalités
1.  **Data Wrangling :** Nettoyage et transformation des données électorales avec `dplyr`.
2.  **Analyse Exploratoire (EDA) :** Visualisation des distributions de votes.
3.  **Clustering (K-Means) :** Segmentation des départements.
4.  **Visualisation Avancée :** Création de graphiques prêts pour la publication avec `ggplot2`.

## 📂 Structure
├── data/          # Données sources
├── R/             # Scripts d'analyse (.R)
└── plots/         # Graphiques exportés (.png)

## 👤 Auteur

**BOUDALIA MONSEF**


