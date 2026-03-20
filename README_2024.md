# 🚗 Challenge Data Visualisation 2024 — Institut des Actuaires

> **Équipe BBM** | Décembre 2024

---

## 📌 Présentation du projet

Ce projet a été réalisé dans le cadre du **Challenge Data Visualisation 2024** organisé par l'Institut des Actuaires. Il propose un dashboard interactif de visualisation statistique des **accidents corporels de la circulation routière en France** pour l'année 2023.

Les données sont issues de la base publique mise à disposition par l'État sur [data.gouv.fr](https://www.data.gouv.fr/fr/datasets/bases-de-donnees-annuelles-des-accidents-corporels-de-la-circulation-routiere-annees-de-2005-a-2023/).

---

## 🗂️ Structure du rapport

Le dashboard s'articule autour de quatre grandes parties :

### 1. 📊 Présentation des données
Vue d'ensemble de la base de données : répartition des accidents dans le **temps**, dans l'**espace** et caractéristiques des **personnes impliquées**.

### 2. 🔍 Étude du contexte des accidents
Analyse des facteurs contextuels qui entourent la survenance des accidents :
- Répartition annuelle et saisonnière (heatmap calendaire par mois/jour de la semaine)
- Répartition horaire des accidents
- Conditions environnementales (météo, luminosité, type de voie…)

### 3. ⚠️ Analyse des critères qui impactent la gravité
Identification et quantification des variables explicatives de la **sévérité** des accidents (type de collision, infrastructure, vitesse, équipements…).

### 4. 💀 Analyse spécifique aux décès
Focus sur les accidents mortels : profil des victimes, facteurs de surmortalité, distribution géographique.

---

## 🛠️ Stack technique

| Outil | Usage |
|---|---|
| **R** | Traitement des données et analyses statistiques |
| **ggplot2** | Visualisations statiques |
| **R Markdown / Quarto** | Génération du rapport HTML interactif |
| **Leaflet** | Cartographies interactives |
| **Wesanderson** | Palettes de couleurs |

---

## 📁 Fichiers

```
.
├── index.html          # Dashboard interactif (rapport final)
├── rapport_2024.Rmd    # Source R Markdown
└── README.md
```

---

## 👥 Équipe

**Équipe BBM** — Challenge Data Visualisation, Institut des Actuaires 2024.

---

## 📄 Licence

Les données utilisées sont en open data sous [Licence Ouverte / Open Licence v2.0](https://www.etalab.gouv.fr/licence-ouverte-open-licence) (Etalab).
