# 🎮 Tic-Tac-Toe Game

Un jeu de morpion moderne développé avec React et Vite, offrant une expérience utilisateur fluide et interactive.

## 📋 Table des matières

- [Aperçu](#aperçu)
- [Fonctionnalités](#fonctionnalités)
- [Technologies utilisées](#technologies-utilisées)
- [Installation](#installation)
- [Utilisation](#utilisation)
- [Structure du projet](#structure-du-projet)
- [Composants](#composants)
- [Règles du jeu](#règles-du-jeu)
- [Contribution](#contribution)
- [Licence](#licence)

## 🎯 Aperçu

Ce projet est une implémentation moderne du jeu classique Tic-Tac-Toe (Morpion) utilisant React. Il propose une interface utilisateur élégante avec des animations et une gestion complète de l'état du jeu.

### Capture d'écran
![Tic-Tac-Toe Game](./public/game-logo.png)

## ✨ Fonctionnalités

- 🎮 **Jeu interactif** : Interface utilisateur intuitive et responsive
- 👥 **Deux joueurs** : Alternance automatique entre les joueurs X et O
- ✏️ **Noms personnalisables** : Possibilité de modifier les noms des joueurs
- 🏆 **Détection de victoire** : Reconnaissance automatique des combinaisons gagnantes
- 🔄 **Fonction restart** : Redémarrage rapide d'une nouvelle partie
- 📊 **Historique des coups** : Affichage de tous les mouvements effectués
- 🎨 **Design moderne** : Interface élégante avec animations CSS
- 🚫 **Prévention des coups invalides** : Impossible de jouer sur une case déjà occupée

## 🛠️ Technologies utilisées

- **React 19.0.0** - Bibliothèque JavaScript pour l'interface utilisateur
- **Vite 4.4.5** - Outil de build rapide et serveur de développement
- **JavaScript ES6+** - Langage de programmation moderne
- **CSS3** - Styles et animations
- **HTML5** - Structure de base

## 🚀 Installation

### Prérequis
- Node.js (version 16 ou supérieure)
- npm ou yarn

### Étapes d'installation

1. **Cloner le repository**
   ```bash
   git clone https://github.com/Pedrocito97/tic-tac-toe-game.git
   cd tic-tac-toe-game
   ```

2. **Installer les dépendances**
   ```bash
   npm install
   ```

3. **Lancer le serveur de développement**
   ```bash
   npm run dev
   ```

4. **Ouvrir dans le navigateur**
   ```
   http://localhost:5173
   ```

## 🎮 Utilisation

### Démarrer une partie
1. Ouvrez l'application dans votre navigateur
2. Le joueur X commence toujours en premier
3. Cliquez sur une case vide pour placer votre symbole
4. Les joueurs alternent automatiquement

### Personnaliser les noms
1. Cliquez sur le bouton "Edit" à côté du nom d'un joueur
2. Saisissez le nouveau nom
3. Cliquez sur "Save" pour confirmer

### Redémarrer une partie
- Cliquez sur le bouton "Rematch!" après la fin d'une partie

## 📁 Structure du projet

```
tic-tac-toe-game/
├── public/
│   ├── game-logo.png
│   └── bg-pattern-dark.png
├── src/
│   ├── components/
│   │   ├── GameBoard.jsx      # Plateau de jeu
│   │   ├── Player.jsx         # Composant joueur
│   │   ├── GameOver.jsx       # Écran de fin de partie
│   │   └── Log.jsx           # Historique des coups
│   ├── App.jsx               # Composant principal
│   ├── index.jsx             # Point d'entrée
│   ├── index.css             # Styles globaux
│   └── winning-combination.js # Combinaisons gagnantes
├── package.json
├── vite.config.js
└── README.md
```

## 🧩 Composants

### `App.jsx`
- Composant principal qui gère l'état global du jeu
- Gère l'alternance des joueurs
- Détecte les conditions de victoire et de match nul
- Coordonne tous les autres composants

### `GameBoard.jsx`
- Affiche le plateau de jeu 3x3
- Gère les clics sur les cases
- Empêche les coups sur les cases déjà occupées

### `Player.jsx`
- Affiche les informations des joueurs
- Permet l'édition des noms
- Indique le joueur actif

### `GameOver.jsx`
- Affiche l'écran de fin de partie
- Annonce le gagnant ou le match nul
- Propose de redémarrer une partie

### `Log.jsx`
- Affiche l'historique de tous les coups joués
- Utile pour suivre le déroulement de la partie

## 🎯 Règles du jeu

1. **Objectif** : Aligner 3 symboles identiques (horizontalement, verticalement ou en diagonale)

2. **Déroulement** :
   - Le joueur X commence toujours
   - Les joueurs alternent à chaque coup
   - Un coup consiste à placer son symbole dans une case vide

3. **Conditions de victoire** :
   - 3 symboles alignés horizontalement
   - 3 symboles alignés verticalement  
   - 3 symboles alignés en diagonale

4. **Match nul** : Toutes les cases sont remplies sans qu'aucun joueur n'ait gagné

## 🤝 Contribution

Les contributions sont les bienvenues ! Pour contribuer :

1. Fork le projet
2. Créez une branche pour votre fonctionnalité (`git checkout -b feature/AmazingFeature`)
3. Committez vos changements (`git commit -m 'Add some AmazingFeature'`)
4. Push vers la branche (`git push origin feature/AmazingFeature`)
5. Ouvrez une Pull Request

## 📝 Scripts disponibles

- `npm run dev` - Lance le serveur de développement
- `npm run build` - Construit l'application pour la production
- `npm run preview` - Prévisualise la version de production
- `npm run lint` - Vérifie le code avec ESLint

## 🐛 Problèmes connus

Aucun problème connu actuellement. Si vous rencontrez un bug, n'hésitez pas à ouvrir une issue.

## 📄 Licence

Ce projet est sous licence MIT. Voir le fichier `LICENSE` pour plus de détails.

## 👨‍💻 Auteur

**Pedrocito97**
- GitHub: [@Pedrocito97](https://github.com/Pedrocito97)

---

⭐ N'hésitez pas à donner une étoile si ce projet vous a plu ! 