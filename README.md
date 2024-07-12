# Ydenn Mobile

Ydenn est une plateforme qui propose des espaces d’échange et de discussions sur des thématiques en respectant les règles de bienséance. Cette application mobile vise à offrir une alternative sécurisée et bienveillante aux réseaux sociaux traditionnels.

## Table des matières

- [Fonctionnalités](#fonctionnalités)
- [Prérequis](#prérequis)
- [Installation](#installation)
- [Démarrage](#démarrage)
- [Structure du projet](#structure-du-projet)

## Fonctionnalités

- Création de compte et connexion sécurisée
- Espaces de discussion thématiques
- Anonymat contrôlé
- Système de ludification avec badges et points
- Notifications push

## Prérequis

Avant de commencer, assurez-vous d'avoir les outils suivants installés sur votre machine :

- [Node.js](https://nodejs.org/) (version 14.x ou supérieure)
- [Git](https://git-scm.com/)

## Installation

1. Clonez le repository :

   ```bash
   git clone https://github.com/votre-utilisateur/ydenn-mobile.git
   cd ydenn-mobile
   ```

2. Installez les dépendances :

   ```bash
   npm install
   ```

## Démarrage

Pour démarrer l'application en mode développement avec Expo, exécutez la commande suivante :

```bash
npx expo start
```

Scannez le code QR avec l'application Expo Go sur votre téléphone pour voir l'application en action.

## Structure du projet

Voici une vue d'ensemble de la structure du projet :

```bash
ydenn-mobile/
├── app/                     # Code source de l'application
│   ├── (auth)/              # Ecrans principaux de l'application
│   ├── (tabs)/              # Services et API
│   ├── _layout.tsx          # Point d'entrée de l'application
│   └── index.tsx            # Point d'entrée de l'application
├── assets/                  # Images, polices et autres ressources statiques
│── components/              # Composants réutilisables
│── constants/               # Composants réutilisables
├── .gitignore               # Fichiers et dossiers à ignorer par Git
├── app.json                 # Configuration de l'application Expo
├── package.json             # Dépendances npm et scripts
├── README.md                # Documentation du projet
└── tailwind.config.js       # Documentation du projet
```
