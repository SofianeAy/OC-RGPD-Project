# OC-RGPD-Project

# Mission 1 : Définition du cadre
#Lire la documentation : Règles de conformité au RGPD
Identifier les règles de protection des données à respecter en fonction des données.
Identifier les interlocuteurs de l'organisation à contacter sur la confidentialité des données.
Se connecter à la base SQL avec SQLite Studio et examiner les données contenues dans le CRM.
Rédiger au moins 5 recommandations sur les règles de gestion à mettre en place sur les données du CRM pour être conforme au RGPD sous forme d’une synthèse de 2 pages au format pdf.

# Mission 2 : Récupération des données
Extraction des données de l’année en cours (la demande d’assurance a été effectuée en 2022) pour les clients dont l’état du dossier est « complet » à partir de la base SQL.
Sélectionner uniquement les données strictement nécessaires.

# Mission 3 : Nettoyage du jeu de données
Préparation du jeu de données pour qu’il soit compatible avec les grands principes du RGPD (ex: utiliser Power Query pour adapter le jeu de données de façon à ce qu’on ne puisse pas croiser les informations pour remonter à l’utilisateur : on peut par exemple remplacer les revenus par un intervalle ([0, 20k€], [20k€, 40k€], etc.), remplacer le nombre d’enfant par une valeur binaire pour indiquer leur présence ou non (Oui/Non), remplacer l’identifiant client par un index aléatoire, etc.
Préparation du jeu de données pour respecter les consignes concernant les données tarifaires.
Noter les préconisations à faire pour les principes qui ne seraient pas immédiatement applicables sur les données.
Documentation : L'anonymisation de données personnelles | CNIL

# Mission 4 : Documentation des traitements des données et rédaction des préconisations à destination de la direction.
Démontrer dans un rapport le respect des processus qualité appliqués et préconisés dans la collecte et la préparation des données.
Exploiter le template de rapport.
Inclure des captures d’écran illustrant les traitements effectués.

#Mission 5 : Présentation à la directrice
S'assurer que la directrice soit familière avec les termes techniques. Limiter et expliquer le vocabulaire spécifique employé.
Adopter un ton rassurant.
