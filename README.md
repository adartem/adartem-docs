# 📖 ADARTEM – Documentation

Bienvenue dans le dépôt **adartem-docs**, qui héberge la documentation officielle de l’organisation **ADARTEM** et du projet **AdLib** (bibliothèque d’attributs `ad-*`).

La documentation est construite avec **[VitePress](https://vitepress.dev/)** et déployée automatiquement via **GitHub Pages**.

---

## 🚀 Installation

Cloner le dépôt puis installer les dépendances :

git clone git@github.com:adartem/adartem-docs.git
cd adartem-docs
npm install

🛠️ Scripts disponibles

Commande Description
npm run dev Lancer un serveur local de la doc (hot reload)
npm run build Générer le site statique dans build/
npm run serve Servir le build statique (test de prod localement)
npm run lint Vérifier la qualité du code avec ESLint
npm run lint:fix Corriger automatiquement les problèmes de lint
npm run format:check Vérifier le formatage du code (Prettier)
npm run format:write Appliquer le formatage automatiquement
npm run test Lancer les tests (placeholder pour l’instant)

🧩 Arborescence

adartem-docs/
├── docs/ # Contenu de la documentation (Markdown)
│ ├── guide/ # Guides utilisateur
│ ├── index.md # Page d’accueil
│ └── ...
├── .github/ # Workflows CI/CD, templates PR/Issues
├── build/ # Résultat du build statique (ignored par git)
├── package.json
├── eslint.config.js
├── .prettierrc.json
└── tsconfig.json

🔄 CI/CD & Déploiement

Les workflows GitHub Actions gèrent automatiquement :

CI (main & develop) :

Lint (eslint)

Format (prettier --check)

Tests (npm run test)

Build (vitepress build docs)

Upload de l’artefact docs-build

Release (main) :

Build de la doc

Déploiement automatique sur GitHub Pages

👉 Le site est publié automatiquement sur :
https://adartem.github.io/adartem-docs/

🤝 Contribution

Fork du dépôt

Créer une branche (git checkout -b feature/ma-feature)

Commit avec un message clair (feat: ajout section installation)

Push et ouvrir une Pull Request

👉 Voir CONTRIBUTING.md pour les règles détaillées.

📜 Licence

Ce projet est sous licence MIT.
Voir le fichier LICENSE pour plus d’informations.
