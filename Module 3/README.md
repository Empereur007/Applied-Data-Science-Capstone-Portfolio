# 📍 Module 3 – Analyse Visuelle Interactive et Tableaux de Bord
## 📖 Présentation
Ce module est consacré à l'exploration interactive des données du projet **SpaceX Falcon 9 Landing Prediction**.
Après l'analyse exploratoire réalisée dans le module précédent, les données sont ici représentées sous forme de **cartes interactives** et de **tableaux de bord dynamiques** afin de faciliter leur interprétation et d'offrir une meilleure expérience utilisateur.
Les travaux sont réalisés à l'aide des bibliothèques **Folium**, **Plotly** et **Dash**.
---
# 🎯 Objectifs
Les objectifs de ce module sont les suivants :
- Visualiser les sites de lancement sur une carte interactive.
- Explorer les données géographiques à l'aide de Folium.
- Concevoir un tableau de bord interactif avec Plotly Dash.
- Permettre l'exploration dynamique des données grâce à des filtres et des graphiques interactifs.
- Mettre en pratique les principes de la visualisation interactive des données.
---
# 📂 Contenu du module
## 🔹 Lab 1 – Analyse visuelle interactive avec Folium
Ce laboratoire consiste à représenter les différents sites de lancement SpaceX sur une carte interactive.
Les principales activités réalisées sont :
- affichage des sites de lancement ;
- ajout de marqueurs sur la carte ;
- visualisation des zones de lancement ;
- calcul et affichage des distances entre les sites et différents points d'intérêt ;
- interprétation des données géographiques.
**Compétences développées**
- Folium
- Cartographie interactive
- Géovisualisation
- Analyse spatiale
---
## 🔹 Lab 2 – Construction d'un tableau de bord interactif avec Plotly Dash
Dans ce laboratoire, une application web interactive est développée afin d'explorer les données des lancements SpaceX.
Le tableau de bord permet notamment :
- de sélectionner un ou plusieurs sites de lancement ;
- de visualiser le nombre de lancements réussis ;
- d'explorer la relation entre la charge utile (*Payload Mass*) et le succès des lancements ;
- de filtrer dynamiquement les données grâce aux composants interactifs de Dash.
**Compétences développées**
- Plotly
- Dash
- Callbacks
- Développement d'applications web interactives
- Visualisation dynamique des données
---
# 📁 Structure du dossier
```text
Module-3-Interactive-Visual-Analytics/
│
├── README.md
├── requirements.txt
│
├── notebooks/
│   └── Interactive_Visual_Analysis_Folium.ipynb
│
├── datasets/
│   └── spacex_launch_dash.csv
├── dashboard/
│   └── spacex_dash_app.py
│
└── images/
    ├── Dash1.png
    ├── Dash2.png
    ├── Dash3.png
    ├── Dash4.png
    ├── Dash4.png
    └── Dash6.png
```
---
# 🛠️ Technologies utilisées
- Python
- Jupyter Notebook
- Pandas
- Plotly
- Dash
- Folium
- HTML
- CSS (Dash Components)
---
# 🎓 Compétences acquises
À l'issue de ce module, je suis capable de :
- créer des cartes interactives avec Folium ;
- représenter des données géographiques ;
- développer un tableau de bord interactif avec Plotly Dash ;
- utiliser les callbacks de Dash pour créer des interactions dynamiques ;
- concevoir une application web simple de visualisation de données.
---
# ➡️ Suite du projet
Les analyses interactives réalisées dans ce module permettront d'identifier les variables les plus pertinentes avant de passer au **Module 4**, consacré à l'analyse prédictive et à la construction de modèles de classification.
