# Titre de la compétence

> ❌ A travailler

> ✔️ Auto validation par l'étudiant

## 🎓 J'ai compris et je peux expliquer

- Comment développer en utilisant un système de _livereloading_ (`nodemon` par exemple) ✔️
  Nodemon surveille notre code pour les changements. Chaque fois que notre code change, nodemon redémarre automatiquement notre application Node.js afin qu'elle récupère notre code mis à jour.
  Tout d'abord, nous devons installer le package Nodemon, exécuter npm install nodemon maintenant, vous devez ajouter un script dans le fichier package.json.
  ex:
  "start:dev": "nodemon index.js" - index.js étant un point d'entrée assez courant pour une application Node.js)

Nous n'utilisons pas nodemon ici car l'utilisation de npm start est le moyen typique de démarrer une application Node.js en production, et nous ne devrions pas utiliser nodemon ou le rechargement en direct en production.

Ensuite, nous pouvons configurer nodemon avec un nodemon.json. Nous pouvons spécifier les fichiers à surveiller pour les modifications. Nous pouvons également indiquer à nodemon quels champs ignorer. Avec le champ 'exec', nous pouvons configurer nodemon pour invoquer le nœud src/index.js. Cela signifie que nous pouvons simplement invoquer npx nodemon sans paramètres et qu'il sait quelle commande exécuter en regardant dans son fichier de configuration.
ex: nodemon.js

```
{
    "watch": [
        "src/"
    ],
    "ignore": [
        "src/test/"
    ],
    "exec": "node src/index.js"
}
```

- La connexion de mon application à une base de données avec et sans ORM/ODM (avec `mongodb` puis `mongoose` par exemple) ❌ / ✔️
  La principale différence est que ORM est destiné aux bases de données MySQL, tandis qu'ODM effectue le mappage pour la représentation documentaire des données. La meilleure façon de se souvenir de ce que fait ORM serait de le considérer comme une feuille de calcul Excel, avec des lignes et des colonnes.

- Le développement d'une API REST et GraphQL (avec les packages `express` et `graphql` par exemple) ❌ / ✔️
- _Bonus : la manipulation des fichiers système avec `fs` et l'utilisation des streams en NodeJS_ ❌ / ✔️

## 💻 J'utilise

### Un exemple personnel commenté ❌ / ✔️

```javascript
// this function takes a path to a .md file of the host system and write the HTML version of this file
// the .html file is given back
const convertMDFileToHTML = (pathToMDfile) => /* ... path to HTML file */
```

### Utilisation dans un projet ❌ / ✔️

[lien github](...)

Description :

### Utilisation en production si applicable❌ / ✔️

[lien du projet](...)

Description :

### Utilisation en environement professionnel ❌ / ✔️

Description :

## 🌐 J'utilise des ressources

### Titre

- lien
- description

## 🚧 Je franchis les obstacles

### Point de blocage ❌ / ✔️

Description:

Plan d'action : (à valider par le formateur)

- action 1 ❌ / ✔️
- action 2 ❌ / ✔️
- ...

Résolution :

## 📽️ J'en fais la démonstration

- J'ai ecrit un [tutoriel](...) ❌ / ✔️
- J'ai fait une [présentation](...) ❌ / ✔️
