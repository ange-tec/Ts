# Mini Projet TypeScript avec Vite

Ce projet est un projet minimal utilisant [Vite](https://vitejs.dev/) et [TypeScript](https://www.typescriptlang.org/) pour une liste d'éléments.

## Prérequis

Assurez-vous d'avoir installé les éléments suivants sur votre machine :

- [Node.js](https://nodejs.org/) (version 16+ recommandée)
- [npm](https://www.npmjs.com/) ou [yarn](https://yarnpkg.com/) installé

## Installation

Clonez ce dépôt et installez les dépendances :

```sh
git clone <URL_DU_REPO>
cd <NOM_DU_PROJET>
npm install  # ou yarn install
```

## Démarrer le projet

Pour lancer le serveur de développement, utilisez la commande suivante :

```sh
npm run dev  # ou yarn dev
```

Ensuite, ouvrez votre navigateur et accédez à l'URL affichée dans la console (généralement `http://localhost:5173`).

## Compilation pour la production

Pour générer les fichiers de production optimisés :

```sh
npm run build  # ou yarn build
```

Les fichiers seront générés dans le dossier `dist/`.

## Structure du projet

Voici une structure typique du projet :

```
/NOM_DU_PROJET
│── public/          # Fichiers statiques
│── src/             # Code source TypeScript
│   ├── main.ts      # Point d'entrée principal
│   ├── App.tsx      # Composant principal (si React est utilisé)
│── tsconfig.json    # Configuration TypeScript
│── vite.config.ts   # Configuration Vite
│── package.json     # Dépendances et scripts
└── README.md        # Documentation
```

## Scripts disponibles

- `npm run dev` : Démarrer le serveur de développement
- `npm run build` : Construire le projet pour la production
- `npm run preview` : Aperçu du build de production
- `npm run lint` : Vérifier la qualité du code (si ESLint est configuré)

## Technologies utilisées

- [Vite](https://vitejs.dev/) pour le bundling rapide
- [TypeScript](https://www.typescriptlang.org/) pour un typage robuste
- [ESLint](https://eslint.org/) (optionnel) pour la qualité du code
- [Prettier](https://prettier.io/) (optionnel) pour le formatage automatique

## Contribuer

Si vous souhaitez contribuer :

1. Forkez ce dépôt
2. Créez une branche (`git checkout -b feature/nom-de-la-feature`)
3. Commitez vos modifications (`git commit -m 'Ajout de la feature X'`)
4. Poussez sur la branche (`git push origin feature/nom-de-la-feature`)
5. Ouvrez une Pull Request

## Licence

Ce projet est sous licence MIT. Voir le fichier [LICENSE](LICENSE) pour plus d'informations.
