# Suivi des Dépenses Multi-Utilisateurs

Application web full-stack permettant à plusieurs utilisateurs de suivre et gérer leurs dépenses personnelles de façon sécurisée et indépendante.

## 🎯 Fonctionnalités

- **Authentification sécurisée** : Inscription et connexion multi-utilisateurs.
- **Gestion cloisonnée** : Chaque utilisateur accède uniquement à ses propres données.
- **Gestion des dépenses (CRUD)** : Ajout, modification, affichage et suppression des dépenses.
- **Catégorisation & Filtrage** : Organisation des dépenses par catégorie et par période.
- **Tableau de bord** : Visualisation globale du budget et suivi du résumé financier.

## 🛠️ Technologies utilisées

- **Backend** : Laravel (PHP)
- **Frontend** : React
- **Base de données** : MySQL
- **Containerisation** : Docker & Docker Compose
- **Contrôle de version** : Git

## 📌 Contexte

Projet réalisé dans le cadre de mon cursus académique en Génie Logiciel à l'Université Iba Der Thiam de Thiès pour mettre en pratique le développement d'une application full-stack complète, de la conception de la base de données à l'interface utilisateur.

## 🚀 Installation & Lancement

### Option 1 : Lancement rapide avec Docker (Recommandé)

```bash
# Cloner le projet
git clone [https://github.com/salamata-dia/suivi-depenses-multi-utilisateurs.git](https://github.com/salamata-dia/suivi-depenses-multi-utilisateurs.git)
cd suivi-depenses-multi-utilisateurs

# Lancer les conteneurs
docker-compose up -d --build
