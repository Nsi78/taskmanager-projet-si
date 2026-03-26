# 📋 TaskManager API - Projet SI (ESIEE IT)

Ce projet est le livrable final du cours **"Projet SI : Mise en pratique avec Java"** (ESIEE IT). Il s'agit d'une API REST de gestion de tâches basée sur une architecture MVC standard.

## 🛠️ Technologies Utilisées
- **Java 17**
- **Spring Boot 3.2.5** (Web, Data JPA)
- **MySQL 8** (via Docker)
- **Spring Security** avec JWT (JJWT 0.12.5) pour l'authentification

## 🚀 Fonctionnalités implémentées
- Inscription et connexion des utilisateurs avec hachage des mots de passe.
- Sécurisation des routes avec token JWT.
- Création et récupération des tâches.
- Modèle MVC (Controllers, Services, Repositories, Models).

## ⚙️ Comment lancer le projet ?

**1. Démarrer la base de données MySQL**
À la racine du projet, lancez le conteneur via Docker :
\`\`\`bash
docker-compose up -d
\`\`\`

**2. Lancer l'API Spring Boot**
Lancez le projet depuis votre IDE (fichier `TaskmanagerApplication.java`) ou via la commande Gradle :
\`\`\`bash
./gradlew bootRun
\`\`\`

---
**Réalisé par :** Matteo Betsch / Eness Hicette / Farell Akakpo
