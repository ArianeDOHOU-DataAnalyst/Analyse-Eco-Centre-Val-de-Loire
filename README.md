📊 Analyse Économique et Typologie des Territoires de la Région Centre-Val de Loire (2025)

📌 Présentation du Projet
Ce projet propose un diagnostic approfondi du tissu économique de la Région Centre-Val de Loire. L'objectif est de dépasser les frontières administratives pour révéler la géographie fonctionnelle du territoire grâce à l'analyse de données massives (Big Data).

🛠️ Stack Technique & Méthodologie
Langage : Python (Pandas, Scikit-Learn, Plotly, GeoPandas).
Données : Fusion des bases Sirene (INSEE) pour la structure et URSSAF (T1 2025) pour l'emploi et les salaires.
Nettoyage : Exclusion du secteur agricole (8% des établissements) pour garantir l'alignement des sources de données salariales.
Algorithme : Clustering K-Means (k=4) validé par la méthode du coude pour définir l'ADN économique des EPCI.

📈 Chiffres Clés (Portrait Régional)
Établissements : 73 471 employeurs.
Salariés : 667 472 effectifs.
Salaire Moyen : 2 627 € / mois.
Dualité : L'industrie représente 8,2% des entreprises mais concentre 21,9% des emplois.

🗺️ Résultats du Clustering (Typologies d'EPCI)
L'analyse a identifié deux grandes familles de territoires structurantes:
Profil A - Socle Rural et de Proximité (55 EPCI) : Économie présentielle basée sur le commerce, la construction et les services locaux.
Profil B - Pôles Urbains et de Services (25 EPCI) : Moteurs de croissance concentrant l'emploi qualifié et l'innovation (ex: Orléans, Tours).
Profils C & D : Artefacts statistiques isolant des territoires limitrophes atypiques.

💡 Préconisations Stratégiques
Pour le Socle Rural : Soutenir la transition numérique/écologique des TPE et revitaliser les centres-bourgs.
Pour les Pôles Urbains : Renforcer l'attractivité pour les talents et créer des campus d'excellence thématiques.

📂 Structure du Dépôt
├── notebooks/  # Analyse Python (Nettoyage & K-Means) [
├── output/     # Visualisations, Cartes et Tableaux de bord
├── reports/    # Rapport d'étude complet (PDF) 
└── requirements.txt # Dépendances du projet

🚀 Comment utiliser ce projet
Cloner le dépôt : git clone  https://github.com/ArianeDOHOU-DataAnalyst/Analyse-Eco-Centre-Val-de-Loire.git
Installer les dépendances : pip install -r requirements.txt
Explorer le notebook : jupyter notebook notebooks/Etude_sur_les_regions_clustering.ipynb