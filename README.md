# Atelier Seaborn – Analyse de données IoT

##  Description

Cet atelier a pour objectif de réaliser une analyse exploratoire de données (EDA) à partir de données provenant de capteurs IoT installés dans plusieurs bâtiments.

Chaque capteur collecte différentes informations :

- température ;
- humidité relative ;
- pression ;
- consommation énergétique ;
- état du capteur ;
- bâtiment ;
- date et heure de la mesure.

Après avoir utilisé NumPy, Pandas et Matplotlib, cet atelier permet d'utiliser **Seaborn** afin de réaliser des visualisations statistiques plus riches et d'analyser les relations entre les différentes variables.

---

##  Objectifs

L'objectif de cet atelier est de :

- importer et explorer un dataset IoT ;
- analyser la distribution des températures ;
- comparer les températures entre les bâtiments ;
- analyser les états des capteurs ;
- étudier la relation entre température et consommation ;
- réaliser des régressions ;
- calculer et visualiser les corrélations ;
- réaliser une analyse multivariée ;
- sauvegarder les graphiques générés ;


---

## Technologies utilisées

- **Python**
- **Pandas** : manipulation et analyse des données
- **NumPy** : manipulation des données numériques
- **Matplotlib** : visualisation
- **Seaborn** : visualisation statistique
- **Jupyter Notebook** : réalisation de l'atelier

## Fonctionnalité bonus

Une fonctionnalité supplémentaire a été ajoutée afin de faciliter la comparaison des températures entre les différents bâtiments.

Cette fonctionnalité utilise `groupby()` et `agg()` de Pandas pour calculer, pour chaque bâtiment :

- la température moyenne ;
- la température médiane ;
- la température minimale ;
- la température maximale.

Elle permet d'obtenir rapidement une vue synthétique des températures enregistrées dans chaque bâtiment et d'identifier les bâtiments présentant les températures moyennes les plus élevées ou les plus faibles.


---

##  Structure du projet

```text
atelier_seaborn_iot/
│
├── data/
│   └── mesures_capteurs.csv
│
├── notebooks/
│   └── atelier_seaborn_iot.ipynb
│
├── exports/
│   ├── temperature.png
│   ├── temperature.pdf
│   └── ...
│
└── README.md

---
