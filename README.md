# 📚 API Backend - Gestion de Catalogue (OpenClassrooms)

## 📋 Description
Ce projet consiste en la conception et le développement d'une **API REST sécurisée** réalisée dans le cadre de ma formation de Développeur Full-Stack. L'objectif était de bâtir une architecture backend robuste pour gérer un catalogue de produits ("Things"), incluant la gestion des utilisateurs et le stockage de médias.

## 🚀 Fonctionnalités clés
*   **Architecture CRUD complète** : Création, lecture, modification et suppression de produits avec validation de données.
*   **Sécurisation des accès** : Implémentation d'une authentification renforcée via **JSON Web Tokens (JWT)**.
*   **Gestion de fichiers** : Système de téléchargement et de stockage d'images optimisé avec le middleware **Multer**.
*   **Persistence des données** : Intégration d'une base de données NoSQL via **MongoDB Atlas** et modélisation via **Mongoose**.

## 🛠️ Stack Technique
*   **Runtime** : Node.js
*   **Framework Web** : Express.js
*   **Base de données** : MongoDB (NoSQL)
*   **Modélisation** : Mongoose
*   **Sécurité** : Bcrypt (hachage de mots de passe), JWT (autorisation)
*   **Gestion d'images** : Multer

## 🏗️ Architecture du Projet
Le projet suit une structure organisée pour assurer la maintenabilité du code :
- `/models` : Définition des schémas de données Mongoose.
- `/controllers` : Logique métier et traitement des requêtes.
- `/routes` : Définition des points d'accès API.
- `/middleware` : Authentification et gestion des fichiers entrants.

## ⚙️ Installation
1. Clonez le dépôt : `git clone [URL-DE-TON-REPO]`
2. Installez les dépendances : `npm install`
3. Configurez vos variables d'environnement (MongoDB URL) dans un fichier `.env`.
4. Lancez le serveur : `node server` (ou `nodemon server` en développement).

---
*Projet réalisé par Jaures Kanga dans le cadre de ma formation continue en développement Full-Stack.*