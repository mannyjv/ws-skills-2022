# TypeScript

> ❌ A travailler

> ✔️ Auto validation par l'étudiant

## 🎓 J'ai compris et je peux expliquer

- l'intéret de TypeScript dans l'IDE ✔️
  TypeScript étend JavaScript et améliore l'expérience du développeur. Il permet aux développeurs d'ajouter une sécurité de type à leurs projets. De plus, TypeScript fournit diverses autres fonctionnalités, telles que les interfaces, les alias de type, les classes abstraites, la surcharge de fonctions, le tuple, les génériques, etc.

- les types de bases ✔️
  String , number , boolean, Arrays, any, function

- comment et pourquoi étendre une interface ✔️
  Utilisez le mot clé extend pour étendre les interfaces dans TypeScript, par ex. interface Chien étend Animal {âge : nombre ;}. Le mot clé extend nous permet de copier les membres d'autres types nommés et d'ajouter de nouveaux membres à l'interface finale, plus générique. Le mot-clé extend supprime le besoin de répéter les membres d'autres types à plusieurs endroits et montre la relation entre les interfaces pour le lecteur du code.

- les classes et les decorators ✔️
  TypeScript a introduit des classes pour tirer parti des techniques orientées objet telles que l'encapsulation et l'abstraction. La classe dans TypeScript est compilée en fonctions JavaScript simples par le compilateur TypeScript pour fonctionner sur toutes les plates-formes et tous les navigateurs. Pour créer et transmettre un objet de classe dont le type est vérifié, nous devons utiliser des classes TypeScript.

Il existe maintenant certains scénarios qui nécessitent des fonctionnalités supplémentaires pour prendre en charge l'annotation ou la modification des classes et des membres de classe. Les décorateurs fournissent un moyen d'ajouter à la fois des annotations et une syntaxe de méta-programmation pour les déclarations de classe et les membres. Les décorateurs sont une proposition d'étape 2 pour JavaScript et sont disponibles en tant que fonctionnalité expérimentale de TypeScript. Lorsque vous appliquez un décorateur à une classe ou à un membre de classe, vous appelez en fait une fonction qui va recevoir des détails sur ce qui est décoré, et l'implémentation du décorateur pourra alors transformer le code dynamiquement, en ajoutant des fonctionnalités supplémentaires, et réduire le code passe-partout. Ils sont un moyen d'avoir une métaprogrammation dans TypeScript, qui est une technique de programmation qui permet au programmeur de créer du code qui utilise un autre code de l'application elle-même comme données.

## 💻 J'utilise

### Un exemple personnel commenté ✔️

```
export default function ({ groups }: { groups: Group[] }): GroupWithSills[] {
  return groups.map((groupObj) => {
    const skillsArrToAdd: string[] = [];
    groupObj.students.forEach((student) => {
      for (const skill of student.skills) {
        if (!skillsArrToAdd.includes(skill)) skillsArrToAdd.push(skill);
      }

    });

    return { ...groupObj, skills: skillsArrToAdd.sort() };
  });
}
```

### Utilisation dans un projet ✔️

[lien github]https://github.com/Sttayllah/WCS-monorepo

Description : Un outil pour créer des blogs simples. Projet de groupe

### Utilisation en production si applicable❌ / ✔️

[lien du projet](...)

Description :

### Utilisation en environement professionnel ✔️

https://www.npmjs.com/package/@wavestreamlabs/wavestream-sdk-ts

Description : La bibliothèque client Wavestream est un SDK Javascript écrit en tapuscrit qui permet une communication transparente avec l'API Wavestream. Les méthodes intégrées facilitent la gestion des vidéos et des opérations de webhooks.

## 🌐 J'utilise des ressources

### Titre

- lien https://www.typescriptlang.org/docs/
- description - docs

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
