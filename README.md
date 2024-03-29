# LITRevu
- Projet 9 de la formation DA PYTHON d'OpenClassrooms
## Description

LITRevu est une application web qui permet aux utilisateurs de demander, lire et publier des critiques de livres ou d'articles.

## Fonctionnalités
### Pour les visiteurs non connectés :
- S'inscrire
- Se connecter

### Pour les utilisateurs connectés :
- Consulter leur flux contenant les derniers billets et les critiques des utilisateurs qu'ils suivent, classés par ordre antichronologique
- Créer de nouveaux billets pour demander des critiques sur un livre ou un article
- Créer de nouvelles critiques en réponse à des billets
- Voir, modifier et supprimer leurs propres billets et critiques
- Suivre d'autres utilisateurs en entrant leur nom d'utilisateur
- Voir qui ils suivent et suivre qui ils veulent
- Arrêter de suivre  un utilisateur

## Spécifications techniques
- Framework : Django
- Base de données : SQLite (le fichier db.sqlite3 est inclus dans le dépôt)
- Respect des directives de la PEP8
- Interface utilisateur propre et minimale

## Installation et exécution
1. Cloner le dépôt
2. Créer un environnement virtuel :
    ```bash
    python3 -m venv env
    ```
3. Activer l'environnement virtuel :
    - Sous Windows :
    ```bash
    env\Scripts\activate
    ```
    - Sous Linux/macOS :
    ```bash
    source env/bin/activate
    ```
4. Installer les dépendances :
    ```bash
    pip install -r requirements.txt
    ```
5. Naviguer vers le répertoire de l'application :
    ```bash
    cd LITRevu
    ```
6. Lancer le serveur :
    ```bash
    py manage.py runserver
    ```
7. Accéder à l'application dans votre navigateur à l'adresse suivante : http://127.0.0.1:8000/

