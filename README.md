# Qualifier-les-architectures-de-r-seaux-hybrides-d-di-es-l-IoT


# Qualifier les Architectures de Réseaux Hybrides Dédiées à l'IoT

## Table des matières
- [Description du Projet](#description-du-projet)
- [Technologies Utilisées](#technologies-utilisées)
- [Fonctionnalités](#fonctionnalités)
- [Installation](#installation)
- [Utilisation](#utilisation)
- [Scripts Python](#scripts-python)
- [Contributions](#contributions)
- [Licence](#licence)
- [Contact](#contact)

## Description du Projet
Ce projet vise à qualifier les architectures de réseaux hybrides dédiées à l'IoT en utilisant Home Assistant pour gérer un système solaire et des prises connectées. Il permet de contrôler et de surveiller la consommation d'énergie de manière centralisée et efficace.

## Technologies Utilisées
- **Home Assistant** : Pour la gestion du système.
- **Python** : Pour l'écriture de scripts de contrôle et de collecte de données.
- **SQLite/MySQL** : Pour la base de données.
- **CSV** : Pour l'exportation des données.

## Fonctionnalités
- Surveillance de la consommation d'énergie des prises connectées.
- Contrôle des prises à distance via Home Assistant.
- Enregistrement des données de consommation dans une base de données.
- Exportation des données en format CSV.

## Installation
1. **Cloner le dépôt :**
   ```bash
   git clone https://github.com/adamchehade/Qualifier-les-architectures-de-r-seaux-hybrides-d-di-es-l-IoT.git
   cd votre-repo
Installer les dépendances :

bash
Copy code
pip install -r requirements.txt
Configurer Home Assistant :

Suivez les instructions de configuration sur le site de Home Assistant.
Configurer la base de données :

Modifiez le fichier config.py pour spécifier les détails de la base de données.
Utilisation
Lancez Home Assistant et connectez vos appareils.
Exécutez le script Python pour commencer à enregistrer les données :
bash
Copy code
python script.py
Scripts Python
Les scripts suivants sont inclus dans le projet :

control_sockets.py : Contrôle des prises connectées.
record_data.py : Enregistre les données de consommation.
export_to_csv.py : Exporte les données en format CSV.
Contributions
Les contributions sont les bienvenues ! Pour contribuer :

Fork le projet.
Créez une branche pour votre fonctionnalité (git checkout -b feature/nouvelle-fonctionnalité).
Committez vos modifications (git commit -m 'Ajout d'une nouvelle fonctionnalité').
Poussez votre branche (git push origin feature/nouvelle-fonctionnalité).
Ouvrez une pull request.
Licence
Ce projet est sous licence MIT. Voir le fichier LICENSE pour plus de détails.

Contact
Pour toute question, veuillez contacter :
Email : chehadeadam84@gmail.com


