**STORY**

Quand la data rencontre la réalité sociale…
Il y a trois semaines, le père de mon ami a dû fermer sa boulangerie.
Deux personnes ont perdu leur emploi.
En discutant avec lui, il m’a parlé d’une notion que je ne connaissais pas : la procédure collective.
C’est une procédure juridique engagée quand une entreprise ne peut plus payer ses dettes.
En approfondissant, j’ai découvert le **BODACC**, le **Bulletin Officiel des Annonces Civiles et Commerciales**.
Un journal officiel qui publie toutes les informations légales sur les entreprises françaises : créations, liquidations, redressements judiciaires…
J’ai donc lancé un projet data pour analyser la situation des entreprises en difficulté.
Ma méthodologie :
1. Identification des sources de données :
Recherche d’API ouvertes et fiables → **API BODACC** (procédures collectives, infos légales...)
2. Définition du périmètre :
Constitution d’un échantillon de 10 000 entreprises en procédure collective
3. Choix des dimensions d’analyse :
   
      - Localisation (départements)
      - Secteur d’activité (classification automatique par mots-clés)
      - Type de procédure (liquidation, redressement…)
      - Date de parution
4. Pré-traitement avancé avec Python :
Pour améliorer l’analyse, j’ai mis en place une fonction de classification automatique des activités économiques par secteur via du nettoyage de texte et détection de mots-clés.

5. Choix des outils :

      - **Talend** pour l’ETL : connexion API + transformation des données
      - **Power BI** pour l’analyse visuelle et dynamique
6. Conception de la maquette :
Un tableau de bord clair, interactif, avec filtres par secteur, type de procédure, date…
7. Réalisation et itérations :
Construction du flux → tests → corrections → enrichissements → publication

🎯 **Objectif :**

Rendre lisible et compréhensible la réalité des entreprises en difficulté en France, à travers la data.
