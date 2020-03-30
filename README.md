# Software Design

# STB

## Medium

Cette spécification définit les fonctionnalitées relatives au fonctionnement d'un site web de lecture/rédaction d'articles.

### Présentation général

#### Besoins :

- Afficher des articles à destination d'un public technique.
- Créer des intéractions au sein d'une communauté ciblé.
- Donner de la visibiliter aux rédacteurs.

#### Fonctions :

| Fonction |                      Nom                       | Criticité |
| -------- | :--------------------------------------------: | --------: |
| F1       | Se connecter en tant qu'utilisateur/rédacteur. |         1 |
| F2       |             Afficher des articles.             |         1 |
| F3       |         Filtrer des articles par tag.          |         2 |
| F4       |             Commenter un article.              |         2 |
| F5       |   Envoyer des notifications aux utlisateurs.   |         3 |
| F6       |              Rédiger des articles              |         1 |

# Métriques

## Type de métrique

| Type       |   Métrique   |
| ---------- | :----------: |
| Ressource  | Utilisateur  |
| Production |   Article    |
| Ressource  | Commentaire  |
| Processus  | Notification |
| Processus  |  Abonnement  |

# Critères de qualité

- Accessibilité/Ergonomie du site
- Maintenabilité
- Résistance aux montées en charges
- Sécurité des données personelles
- Faisabilité

# Conception architectural

## Client:

## Plateforme :

- Application web
- Application Mobile

## Serveur

- Multi instantiation
- Gestion des specificitées du droit régional
- Répartition des flux de connections

## BDD

- Stockage des utilisateurs
- Stockage des articles
- Stockage des commentaires
- Sauvegarde

# Conception détaillé
