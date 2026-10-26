# Le playground

La page où se font les exercices du cours *Introduction à la programmation et
à l'algorithmique* : on y écrit du JavaScript, on l'exécute, et des tests
automatiques disent si c'est juste. Elle ne demande aucune installation.

## L'ouvrir

- **Depuis votre copie du cours** (fork puis clone, voir le
  [chapitre 01](../01-Mise-en-route.md)) : ouvrez `index.html`, dans ce dossier,
  par un double-clic. Il fonctionne même sans connexion.
- **En ligne**, via GitHub Pages, sans rien télécharger :
  **[▶ Ouvrir le playground](https://diginamicacademy.github.io/Intro-programmation-algorithmique/playground/)**.

Les deux sont identiques. Choisissez l'une des deux et tenez-vous-y pendant
toute la formation : le playground garde votre travail dans le navigateur, et
la version en ligne et la version locale ne partagent pas la même mémoire.
Utilisez un navigateur récent : Chrome, Edge ou Firefox.

## Le journal

Le bouton **📓 Journal** produit le fichier qui rassemble tout votre travail,
signé, à télécharger le soir du deuxième jour et à déposer sur Moodle. Le
[chapitre 01](../01-Mise-en-route.md) explique la marche à suivre.

## Ce que contient ce dossier

| Fichier | Rôle |
|---|---|
| `index.html` | la page du playground |
| `playground.js`, `playground.css` | l'interface : exercices, éditeur, console, tests, journal |
| `moteur.js` | l'exécution du code et des tests, à l'écart de la page |
| `schema.js`, `schema.css` | l'éditeur de schémas (diagrammes de flux) |
| `signature.js` | la signature du journal ; fichier compilé, à ne pas modifier |
| `codemirror/` | l'éditeur de code [CodeMirror 5](https://codemirror.net/5/), sous licence MIT |

Les exercices eux-mêmes sont déclarés dans [`../exercices/`](../exercices/),
un fichier par chapitre.
