# Langage Javascript

> ❌ A travailler

> ✔️ Auto validation par l'étudiant

## 🎓 J'ai compris et je peux expliquer

- les `structures` de base du langage ✔️ | Javascript est un langage orienté objet. Les objets, en JavaScript, sont le type de données le plus important et constituent les éléments de base du JavaScript moderne. Il existe des valeurs primitives et non primitives.
- les normes `ecmascript` ✔️
  le ecmascript est une est une norme JavaScript destinée à assurer l'interopérabilité des pages Web entre différents navigateurs. Il est normalisé par Ecma International. ECMAScript est couramment utilisé pour les scripts côté client sur le World Wide Web, et il est de plus en plus utilisé pour écrire des applications et des services côté serveur à l'aide de Node.js et d'autres environnements d'exécution.

- l'utilisation de l'`asynchrone` ✔️
  La programmation asynchrone est une technique qui permet à votre programme de démarrer une tâche potentiellement longue tout en étant capable de répondre à d'autres événements pendant que cette tâche s'exécute, plutôt que d'avoir à attendre que cette tâche soit terminée.

- les spécifités du mot-clef `this` ✔️
  En JavaScript, le mot clé this fait référence à un objet. L'objet dépend de la manière dont il est invoqué (utilisé ou appelé). Le mot-clé this fait référence à différents objets selon la façon dont il est utilisé : Dans une méthode d'objet, this fait référence à l'objet. Seul, cela fait référence à l'objet global.

## 💻 Je code en Javascript

### Un exemple de code commenté ❌ / ✔️

```javascript
function generateWinningNumber() {
  // the math.random returns number between 0 and 1 with decimals, but not including 1. so if we do * 10, we will get number between 0 and 10(not including 10), but * 100 will give us a number up to 0-99 not including 100. it can be a two digit number. so in order to include 10 or 100, we add the + 1 at the end, for example if we returned a number that was .999, we would be able to turn it into 99.9 and the plus 1 will let us reach 100, so itd be 100.9, then we'd round down, and itd be 100.
  return Math.floor(Math.random() * 100) + 1;
}
```

### Utilisation dans un projet ✔️

[lien github] https://github.com/mannyjv/jukePlayer

Description :Juke : Un simple clone spotify pour diffuser votre musique préférée.
Technologies utilisées
Backend : PostgreSql, Sequelize, node.js, express.js
Frontend : React, HTML (utilisant l'élément), Javascript, CSS

### J'ai utilisé ce langage en production ❌ / ✔️

[lien du projet]
Description :

### J'ai utilisé ce langage en environement professionnel ✔️

https://www.npmjs.com/package/@wavestreamlabs/wavestream-sdk-ts

Description : La bibliothèque client Wavestream est un SDK Javascript écrit en tapuscrit qui permet une communication transparente avec l'API Wavestream. Les méthodes intégrées facilitent la gestion des vidéos et des opérations de webhooks.

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

- J'ai ecrit un [tutoriel] ✔️
  https://medium.com/@emmanuel-vazquez06/salting-and-hashing-a-high-level-overview-of-two-methods-used-to-better-secure-passwords-4112a1171184

Description: J'ai écrit un aperçu de haut niveau de deux méthodes utilisées pour mieux sécuriser les mots de passe : salting et hashing

- J'ai fait une [présentation](...) ❌ / ✔️
