# Applied Data Science Capstone Project

## Présentation  
Ce projet est le **cours final** de la spécialisation [IBM Data Science Professional Certificate](https://www.coursera.org/professional-certificates/ibm-data-science).  

L'objectif est d'analyser les données des lancements de **fusées SpaceX Falcon 9** pour prédire si le premier étage d’un lancement pourra être **récupéré et réutilisé**, ce qui permettrait de réduire le coût des lancements spatiaux.

---

## Questions Clés  
- Comment la **masse de la charge utile, le site de lancement, le nombre de vols et les orbites** influencent-ils la récupération du premier étage ?  
- Le **taux de réussite des récupérations** évolue-t-il au fil des années ?  
- Quel **modèle de classification binaire** est le plus adapté pour cette prédiction ?  

---

## Méthodologie  

### Collecte des données  
- Utilisation de l'**API SpaceX Rest** pour obtenir les données de lancement.  
- **Web Scraping de Wikipédia** pour extraire des données historiques.  

### Préparation des données  
- **Filtrage** et **gestion des valeurs manquantes**.  
- **Encodage One-Hot** des variables catégorielles pour la classification.  

### Analyse des données  
- **Exploration des données** avec **visualisations et SQL**.  
- Création de **visualisations interactives** avec **Folium et Plotly Dash**.  

### Modélisation  
- Comparaison de plusieurs modèles de classification :  
  - **Régression logistique**  
  - **SVM (Support Vector Machine)**  
  - **Arbres de décision et Random Forest**  
  - **KNN (K-Nearest Neighbors)**  
- Évaluation des modèles avec des métriques de performance.  

---

## Technologies Utilisées  
- **Python** (Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn)  
- **SQL** pour l’analyse des données  
- **Folium et Plotly Dash** pour la visualisation  
- **API REST et Web Scraping** (BeautifulSoup, Requests)  

---


