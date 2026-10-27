# CarteSUEZ - Cartographie interactive des déchets à l'échelle des IRIS

## Présentation du projet

Ce dépôt GitHub contient les données géographiques et les fichiers nécessaires à la réalisation d'une **carte interactive consacrée à l'analyse territoriale des déchets à l'échelle des IRIS**.

Ce projet s'inscrit dans le cadre d'un **travail de mémoire** portant sur l'étude de la production et de la répartition des déchets dans différents territoires métropolitains. L'objectif est de proposer une représentation cartographique permettant de **visualiser, explorer et comparer les données relatives aux déchets selon les territoires étudiés**.

La carte interactive s'appuie sur des données géographiques au format **GeoJSON**, permettant de représenter les différents périmètres d'étude et de faciliter l'analyse spatiale des phénomènes observés.

---

## Objectifs

La carte a pour principaux objectifs de :

* visualiser les données relatives aux déchets à une échelle géographique fine ;
* représenter les territoires étudiés à l'échelle des **IRIS** ;
* faciliter l'analyse spatiale et territoriale des données ;
* permettre une lecture interactive des informations géographiques ;
* comparer les différents territoires étudiés dans le cadre du mémoire ;
* proposer un support cartographique complémentaire à l'analyse statistique et géographique.

---

## Territoires étudiés

Le dépôt contient actuellement des données géographiques relatives à plusieurs territoires métropolitains, notamment :

* **Dijon**
* **Montauban**
* **Nîmes**
* **Orléans**

Les fichiers GeoJSON permettent de représenter les différents périmètres géographiques utilisés pour la réalisation de la cartographie et l'analyse des données.

> **Remarque :** la liste des territoires peut être amenée à évoluer au cours du développement du projet et de l'avancement du mémoire.

---

## Données géographiques

Les données géographiques sont principalement stockées au format **GeoJSON**.

Ce format permet de représenter des objets géographiques tels que :

* des polygones correspondant aux territoires étudiés ;
* des limites géographiques à l'échelle des IRIS ;
* des informations attributaires associées aux entités géographiques.

Les différents fichiers GeoJSON présents dans le dépôt sont utilisés comme sources de données pour alimenter la carte interactive.

---

## Structure du dépôt

L'organisation actuelle du dépôt comprend notamment :

```text
CarteSUEZ/
│
├── index.html
│
├── *.geojson
│   ├── Données géographiques de Dijon
│   ├── Données géographiques de Montauban
│   ├── Données géographiques de Nîmes
│   ├── Données géographiques d'Orléans
│   └── Autres données géographiques
│
├── geojsonData.Dijon.geojson
├── geojsonData.Montaubann.geojson
├── geojsonData.Nimes.geojson
├── geojsonData.Orléans.geojson
│
├── Dijon-inter2.geojson
├── Dijon-intera.geojson
├── GeoDij.geojson
├── GeoDij99.geojson
│
├── GeoMonto.geojson
│
├── GeoNimes.geojson
│
├── GeoOrl.geojson
├── GeoOrl1.geojson
├── GeoOrl33.geojson
├── GeoOrl4.geojson
├── GeoOrl99.geojson
│
└── README.md
```

> La structure et les noms des fichiers peuvent évoluer en fonction des besoins du projet et de l'intégration de nouvelles données.

---

## Utilisation

Pour consulter la carte interactive en local :

### 1. Cloner le dépôt

```bash
git clone https://github.com/AnicetYAO225/CarteSUEZ.git
```

### 2. Accéder au dossier du projet

```bash
cd CarteSUEZ
```

### 3. Ouvrir la carte

Ouvrir le fichier :

```text
index.html
```

dans un navigateur web.

Pour une utilisation optimale, il est recommandé de servir le projet via un **serveur web local**, notamment lorsque la carte charge des fichiers GeoJSON externes.

---

## Technologies utilisées

Le projet repose principalement sur des technologies web et des formats de données géographiques :

* **HTML** – structure de la page et de l'application cartographique ;
* **JavaScript** – gestion de l'interactivité et de la logique de la carte ;
* **GeoJSON** – stockage et représentation des données géographiques ;
* **Git / GitHub** – gestion des versions et hébergement du code et des données.

---

## Méthodologie

Le principe général du projet consiste à associer des données statistiques ou thématiques relatives aux déchets à des entités géographiques correspondant aux territoires étudiés.

Les données sont ensuite intégrées dans une interface cartographique interactive afin de permettre :

1. l'identification des territoires étudiés ;
2. la visualisation des données à l'échelle des IRIS ;
3. l'exploration des différences spatiales entre les territoires ;
4. la comparaison des situations observées dans les différentes métropoles.

Cette approche permet de compléter l'analyse du mémoire par une **lecture spatiale et interactive des données**.



