# Boiler Plate NodeJs, SvelteKit

## 🌟 Introduction

Salut à tous ! 🎉 Bienvenue sur mon Boiler Plate, un projet conçu pour vous propulser dans le monde de SvelteKit et Node.js sans délai. Ce projet est votre lance-pierre pour le développement créatif, l'ingénierie web et bien plus encore.

## 🚀 Pourquoi ce Projet ?

Vous vous demandez pourquoi contribuer à ce projet ? Voici pourquoi :

- **Collaboration :** Ce n'est pas seulement mon projet, c'est aussi le vôtre. Ensemble, nous pouvons l'améliorer.
- **Sécurité :** J'ai mis l'accent sur des pratiques de sécurité robustes.
- **Natif :** À terme, le but est de minimiser les dépendances et d'utiliser autant que possible des fonctionnalités natives.
  
## ⚠️ Points à Améliorer

- **Documentation :** JSDocs n'est pas encore complètement intégré.
- **Tests :** Les tests backend sont en cours de développement.
- **Langue :** Vous pourrez trouver du code et des commentaires en français, bien que j'essaie de tout traduire en anglais.
- **CSS :** J'utilise SCSS mais pas de CSS dans les composants Svelte. Vous êtes libres d'utiliser SASS pour des inclusions.

## 💻 Installation Rapide

1. **Docker & MongoDB :**
    - Installer [Docker](https://www.docker.com/get-started).
    - Exécuter `docker run --name BoilerPlateSvelteKitDB -p 27018:27017 -d mongo:4.4`

2. **Dépendances :**
    - Frontend : `npm i`
    - Backend : dans le dossier backend, exécuter `npm i`

3. **Playwright :**
    - `npx playwright install`

4. **MailHog :**
    - Télécharger [MailHog](https://github.com/mailhog/MailHog/releases/v1.0.0).

5. **Extensions :**
    - Installer l'extension Prettier sur VSCode.

6. **Lancer Lighthouse :**
    - `lhci autorun --collect.url=http://127.0.0.1:1000 --upload.target=filesystem --upload.outputDir=./lighthouse-reports/`

## 🌐 Accès Local

- Frontend : [http://localhost:1000](http://localhost:1000)
- Backend : [http://localhost:2000](http://localhost:2000)
- Mail : [http://localhost:8025](http://localhost:8025)

## 🎨 Caractéristiques Principales

### SvelteKit -> UITools
- **Cursor :** Curseur personnalisable.
- **Darkmode :** Pour les fans du mode sombre.
- **Notifications :** Gérer les notifications côté serveur.
- **PageTransition :** Transitions de page natives.
- **Preloader :** Pour une expérience utilisateur fluide.
- **ServiceWorker :** PWA est en place.
- **SmoothScroller :** Défilement doux.
- **Translations :** Multilingue.

### Autres
- **ThreeJs :** Insertion vanilla de ThreeJS.
- **SCSS :** Architecture 7-1.
- **MongoDB :** Authentification complète.
- **Tests :** Validation et création de compte avec Playwright.

## 🛠 À Faire

- [ ] Intégrer les RateLimiter sur chaque champ.
- [ ] Intégrer 0Auth.
- [ ] Tests pour les rôles et la langue.
- [ ] Et bien plus...

## 🤝 Contribuer

Votre contribution peut faire de ce projet une référence pour tout développeur SvelteKit. N'hésitez pas à ouvrir des issues, à proposer des améliorations ou à soumettre des PRs.

## 💌 Contact

Si vous avez des questions ou des suggestions, n'hésitez pas à m'envoyer un [mail](mailto:your-email@example.com) ou à ouvrir une issue.

---

Merci d'avoir pris le temps de lire ce README. J'attends vos retours avec impatience ! 😄🚀


env front: 
VITE_MONGO_ONLINE=MongoURI
VITE_MONGO_LOCAL=mongodb://localhost:27018/BoilerPlateSvelteKitDB
VITE_DATABASE_NAME=BoilerPlateSvelteKitDB
VITE_TOKEN_EXPIRY=1
VITE_URL_FRONT=http://127.0.0.1:1000
VITE_URL_FRONT_LOCAL=http://localhost:1000
VITE_URL_BACK=http://localhost:2000
VITE_PORT: 2000
VITE_SECRETKEY=YOURSECRETKEY
VITE_MAIL_HOST=localhost
VITE_MAIL_PORT: 1025
VITE_EMAIL_USER=no_reply@SvelteKit.com
VITE_EMAIL_PASSWORD=passwordTest
VITE_MAIL_SERVER=no_reply@SvelteKit.com
VITE_NODE_ENV=dev
VITE_DB_ENV=atlas

back:
MONGO_ONLINE=MongoURI
MONGO_LOCAL=mongodb://localhost:27018/BoilerPlateSvelteKitDB
DATABASE_NAME=BoilerPlateSvelteKitDB
TOKEN_EXPIRY=1
URL_FRONT=http://127.0.0.1:1000
URL_FRONT_LOCAL=http://localhost:1000
URL_BACK=http://localhost:2000
PORT: 2000
SECRETKEY=YOURSECRETKEY
MAIL_HOST=localhost
MAIL_PORT: 1025
EMAIL_USER=no_reply@SvelteKit.com
EMAIL_PASSWORD=passwordTest
MAIL_SERVER=no_reply@SvelteKit.com
NODE_ENV=dev
DB_ENV=atlas

