# todo-list-js

Application de gestion de taches (Todo List) en **JavaScript vanilla**, sans framework ni dependance, avec persistance des donnees via `localStorage`.

## Demo

Ouvrez simplement `index.html` dans votre navigateur, ou activez GitHub Pages pour ce depot afin d'obtenir une demo en ligne.

## Fonctionnalites

- Ajouter une nouvelle tache
- Marquer une tache comme terminee / non terminee
- Supprimer une tache
- Filtrer les taches (Toutes / En cours / Terminees)
- Effacer toutes les taches terminees en un clic
- Sauvegarde automatique dans le `localStorage` du navigateur (les taches sont conservees apres fermeture de la page)
- Interface responsive et moderne

## Structure du projet

```
todo-list-js/
├── index.html     # Structure de la page
├── style.css      # Mise en forme de l'application
├── script.js      # Logique de l'application (ajout, suppression, filtres, localStorage)
└── README.md
```

## Installation et utilisation

Aucune installation ni dependance necessaire.

```bash
git clone https://github.com/Linkaart/todo-list-js.git
cd todo-list-js
```

Puis ouvrez le fichier `index.html` dans votre navigateur.

## Technologies utilisees

- **HTML5**
- **CSS3** (Flexbox, design responsive)
- **JavaScript (ES6+)** — manipulation du DOM, `localStorage`, gestion d'evenements

## Ameliorations possibles

- Ajout de la modification d'une tache existante (edition en ligne)
- Drag & drop pour reordonner les taches
- Categories ou etiquettes de taches
- Mode sombre / clair

## Licence

Projet libre a but pedagogique.
