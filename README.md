# Applied Data Science Capstone Project

Ce Capstone est le cours final de la spécialisation [IBM Data Science Professional Certificate](https://www.coursera.org/professional-certificates/ibm-data-science) 

📄 Contexte du projet

SpaceX est l’entreprise la plus prospère de l’ère spatiale commerciale, rendant les voyages spatiaux abordables. La société annonce sur son site Internet les lancements de fusées Falcon 9, pour un coût de 62 millions de dollars ; les autres fournisseurs coûtent plus de 165 millions de dollars chacun, une grande partie des économies étant due au fait que SpaceX peut réutiliser le premier étage. Par conséquent, si nous pouvons déterminer si le premier étage atterrira, nous pouvons déterminer le coût d’un lancement. Sur la base d'informations publiques et de modèles d'apprentissage automatique, nous allons prédire si SpaceX réutilisera la première étape.

📄 Questions auxquelles il faut répondre
- Comment des variables telles que la masse de la charge utile, le site de lancement, le nombre de vols et les orbites affectent-elles le succès de l'atterrissage de la première étape ?
- Le taux de débarquements réussis augmente-t-il au fil des années ?
Quel est le meilleur algorithme pouvant être utilisé pour la classification binaire dans ce cas ?

📄 Méthodologie

1. Méthodologie de collecte de données
- Utilisation de l'API SpaceX Rest
- Utiliser le Web Scrapping de Wikipédia
2. Gestion des données effectuée
- Filtrage des données
- Gérer les valeurs manquantes
- Utilisation de One Hot Encoding pour préparer les données à une classification binaire
3. Analyse exploratoire des données (EDA) effectuée à l'aide de la visualisation et de SQL
4. Réalisation d'analyses visuelles interactives à l'aide de Folium et Plotly Dash
5. Analyse prédictive effectuée à l'aide de modèles de classification
  - Construction, réglage et évaluation de modèles de classification pour garantir les meilleurs résultats
