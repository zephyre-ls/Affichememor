# Affichememor
**Projet de création d'une application pratique pour mon quotidien.**

---

## 1. Préparation

### a. Objectifs de l'application

- Créer une application pour gérer les films que j'ai vus avec un affichage simple : titre + affiche. Simple & Efficace.
- Pratique dans mon quotidien (mauvaise mémoire des noms de films mais bonne mémoire des affiches).
- Les films seront classés par années de visionnage.
- Intégrer une API pour récupérer les affiches des films et utiliser une option manuelle si nécessaire.

> De nombreuses applications existent déjà, je le sais. Mais elles ont trop de fonctionnalités et sont souvent remplies de pubs.  
> Je souhaite quelque chose d'épuré et adapté à ma consommation.

### b. La bonne stack technologique adaptée à mon niveau de newbie.

- **Langage :** JavaScript (React pour le front-end).
- **API :** OMDb pour récupérer les affiches.
- **Backend (si nécessaire) :** Node.js pour gérer les requêtes API ou stockage (tu peux envisager de le garder simple sans backend au départ).
- **Stockage local :** LocalStorage ou IndexedDB pour stocker les films vus si tu n’as pas besoin d’une base de données externe.

### c. Préparation des ressources

- Créer un compte sur OMDb API pour récupérer la clé API gratuite.
- Réfléchir à l'interface graphique, couleur, mise en page, adaptabilité, etc.
- Librairies utilisées pour gérer les affiches (ex : react-image).

---

## 2. Développement

### a. Phase 1 : Mise en place du projet

- Initialiser un projet React (par exemple, avec `create-react-app`).
- Configurer le projet avec les dépendances nécessaires (par exemple, Axios pour faire des requêtes HTTP).
- Créer un dossier et des sous-dossiers pour organiser tout le projet.

### b. Phase 2 : Intégration de l’API OMDb

- Créer une fonction pour interroger l'API OMDb avec le titre du film et récupérer l'affiche.
- Gérer la récupération des données : titres, affiches et années de sortie.
- Tester l’API pour voir comment récupérer une affiche de film avec un titre donné.

### c. Phase 3 : Affichage des films dans l’application

- Créer une page d’accueil avec un affichage épuré des films : titre et affiche.
- Ajouter un système de tri par année de visionnage.
- Gérer l’ajout manuel d’un film si l'API ne retourne pas d'affiche.
- Stocker les films vus localement (en utilisant le LocalStorage ou une autre méthode simple).

### d. Phase 4 : Ajout de la fonctionnalité de tri par année

- Créer un tri simple des films par année.
- Ajouter des boutons ou des filtres pour trier les films selon l’année de visionnage.

---

## 3. Améliorations dans le turfu

### a. Ajouter une fonctionnalité mobile

- Lorsque l’application sur ordinateur est stable, envisager d’utiliser React Native pour rendre l’application portable sur Android.
