# ⚙️ Mini-projet Jenkins – CI/CD sur une application statique

Ce projet met en place une **pipeline CI/CD avec Jenkins** pour automatiser le processus de build, test et déploiement d’une application simple.

## 🧱 Stack technique

- Jenkins
- Docker
- Pipeline Jenkinsfile (declarative syntax)
- Application statique

## 📂 Fichiers du projet

- `Dockerfile` : contient l’environnement nécessaire pour l’application
- `Jenkinsfile` : définit les étapes de la pipeline (build, test, etc.)
- `.gitignore` : exclut les fichiers inutiles du suivi Git

## 🔧 Fonctionnalités

- Construction de l’image Docker de l’application
- Tests de qualité (optionnels selon l’app)
- Automatisation du processus de déploiement via Jenkins pipeline

## ▶️ Exécution

1. Cloner le repo
2. Configurer Jenkins avec un job pipeline pointant sur ce repo
3. Lancer la pipeline pour observer les étapes CI/CD automatisées

## 🎯 Objectifs pédagogiques

- Comprendre le fonctionnement d’une pipeline Jenkins
- Savoir structurer un projet CI/CD simple
- Définir un `Jenkinsfile` clair et fonctionnel
