# KasaApp

Bienvenue dans **KasaApp**, une application web responsive développée avec **React 18**. Ce projet simule un site de location immobilière à la manière d’une plateforme comme Airbnb, avec une expérience utilisateur fluide, des animations élégantes et une structure de code maintenable.

---

## 📅 Description

KasaApp permet de consulter différentes fiches de logements à travers une interface claire et moderne. Chaque page affiche des informations détaillées, un carrousel d’images, une description, des équipements et la notation de l'hôte.

Ce projet est basé sur des données locales au format JSON, et il inclut une gestion complète du routing avec des pages dynamiques pour chaque logement et une page 404 personnalisée.

---

## 📚 Fonctionnalités

- Liste de logements à partir de données locales
- Pages de détails pour chaque bien immobilier
- Slideshow/carrousel d’images avec navigation
- Menus déroulants pour la description et les équipements
- Composants réutilisables
- Page d’erreur 404 personnalisée
- Routing complet via `react-router-dom`

---

## 🔧 Installation

1. Clonez le dépôt :

```bash
git clone https://github.com/Occjtzn/KasaApp
```

2. Accédez au dossier du projet :

```bash
cd KasaApp
```

3. Installez les dépendances :

```bash
yarn install
```

4. Lancez le serveur de développement :

```bash
yarn start
```

---

## 🔹 Scripts disponibles

- `yarn start` : Démarre le serveur en mode développement
- `yarn build` : Crée un build optimisé pour la production
- `yarn test` : Lance les tests (si implémentés)
- `yarn eject` : Éjecte la configuration Create React App

---

## 💚 Technologies utilisées

- React 18
- React Router v6
- SCSS pour les styles
- FontAwesome pour les icônes
- EmailJS pour le formulaire de contact (optionnel)
- Create React App (CRA) comme base du projet
- ESLint + Prettier pour la qualité du code

---

## 🔖 Architecture du projet

```
KasaApp/
├── public/
├── src/
│   ├── assets/              # Images et ressources
│   ├── components/          # Composants réutilisables (Header, Footer, etc.)
│   ├── datas/               # Données JSON locales
│   ├── pages/               # Pages principales (Home, About, Logement, etc.)
│   ├── styles/              # Feuilles de styles SCSS
│   ├── App.jsx              # Composant principal de l'application
│   └── index.js             # Point d'entrée React
├── package.json
└── README.md
```

---

## 📇 Auteur

Projet conçu et développé par [Occjtzn](https://github.com/Occjtzn), développeur front-end spécialisé dans la création d’interfaces web modernes, performantes et accessibles.

---

Merci pour votre intérêt pour KasaApp 🏡