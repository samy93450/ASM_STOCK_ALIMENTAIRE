# ASM Stock Alimentaire

Application web progressive pour iPhone : stock alimentaire, dates de péremption, liste de courses, scanner de produits et tickets, guide de congélation et comparaison mensuelle des dépenses.

## Publication sur GitHub Pages

1. Créez un nouveau dépôt GitHub.
2. Décompressez ce ZIP.
3. Envoyez **tout le contenu** à la racine de la branche `main`.
4. Dans GitHub, ouvrez **Settings → Pages**.
5. Dans **Build and deployment**, choisissez **GitHub Actions**.
6. Attendez la fin de l’action **Publier ASM Stock Alimentaire**.

L’application sera disponible à l’adresse indiquée dans la section **Deployments** du dépôt.

## Installation sur iPhone

1. Ouvrez l’adresse GitHub Pages dans Safari.
2. Touchez **Partager**.
3. Choisissez **Sur l’écran d’accueil**.
4. Validez avec **Ajouter**.

L’icône ASM est déjà intégrée pour l’écran d’accueil, l’onglet du navigateur et l’installation PWA.

## Fichiers principaux

- `index.html` : application complète.
- `manifest.webmanifest` : configuration de l’application installable.
- `sw.js` : fonctionnement hors connexion et mise à jour du cache.
- `icon-192.png`, `icon-512.png`, `icon-1024.png` : icônes de l’application.
- `apple-touch-icon.png` : icône spécifique à l’iPhone.
- `.github/workflows/pages.yml` : publication automatique sur GitHub Pages.

Les données personnelles de l’application restent enregistrées localement dans le navigateur de l’appareil.
