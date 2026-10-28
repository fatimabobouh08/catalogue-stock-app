# 🏪 EILCO Tech - Catalogue & Gestion de Stock

Application web de gestion de catalogue et de stock, développée en HTML, CSS (Tailwind) et JavaScript Vanilla. Ce projet a été réalisé dans le cadre d'un projet Scrum.

## ✨ Fonctionnalités

- **Authentification** : Création de compte et connexion avec validation stricte du mot de passe (géré via `localStorage`).
- **Gestion des produits (CRUD)** :
  - Ajouter un produit avec catégories et sous-catégories dynamiques.
  - Afficher la liste avec une barre de recherche en temps réel.
  - Modifier ou supprimer un produit.
- **Gestion des stocks** :
  - Statut automatique : Disponible, Stock limité, Rupture de stock.
  - Formulaire de sortie de stock (déduction).
  - Formulaire de réapprovisionnement.
- **Génération automatique de références** : Création de références uniques basées sur la catégorie, la marque et la version.

## 🛠️ Technologies utilisées

- **HTML5 / CSS3** (avec [Tailwind CSS](https://tailwindcss.com/))
- **JavaScript** (Vanilla)
- **Docker** (Déploiement avec Nginx)
- **GitHub Actions** (Pipeline CI/CD)

## 🚀 Comment lancer le projet

### Option 1 : Directement dans le navigateur
Ouvrez simplement le fichier `frontend/index.html` dans votre navigateur web.

### Option 2 : Avec Docker 🐳
1. Construisez l'image Docker :
   ```bash
   docker build -t eilco-stock-app .
