# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

Ce projet est un environnement conteneurisé pour une application React créée avec Vite. Les instructions ci-dessous expliquent comment construire et exécuter le projet à l'aide de Docker et Docker Compose.

## Prérequis

- **Docker** et **Docker Compose** installés sur votre machine.

## Installation

1. Clonez le dépôt et placez-vous dans le répertoire du projet :

   ```bash
       git clone https://github.com/Design-IHM/medutopia.git
       cd medutopia
   ```
   
2. Exécuter `docker compose up` pour construire et exécuter les conteneurs Docker.
    ```bash
        docker compose up ou docker compose up --build
    ```

3. Ouvrez votre navigateur et accedez à l'application sur `http://localhost:5173`.

4. Pour arrêter le conteneur, utilisez la commande suivante

    ```bash
        docker compose down
    ```
