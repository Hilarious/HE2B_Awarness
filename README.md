# 🎓 Jongle avec ta Vie d'Étudiant - HE2B Edition

Un mini-jeu mobile de type "Guitar Hero" créé pour la HE2B (Haute École Bruxelles-Brabant) où tu incarnes un étudiant qui doit jongler avec les différents aspects de sa vie étudiante.

![HE2B](https://img.shields.io/badge/HE2B-Bruxelles--Brabant-D91A5B)
![React](https://img.shields.io/badge/React-18-61DAFB)
![License](https://img.shields.io/badge/License-MIT-green)

## 🎮 Jouer

**[▶️ JOUER EN LIGNE](https://VOTRE-USERNAME.github.io/VOTRE-REPO/)**

Ou ouvrir `index.html` dans un navigateur.

## 🕹️ Contrôles

| Plateforme | Contrôles |
|------------|-----------|
| 📱 Mobile | Tape sur les 4 boutons |
| ⌨️ Clavier | Touches **D - F - J - K** |

## 🎯 Objectif

- Survivre **90 secondes** en attrapant les objets qui tombent
- Éviter les objets malus (🐛 🦠 😴 😱 🗑️)
- Viser la ligne dorée pour les bonus **×2** et **×3**
- Maintenir ta barre de Focus au-dessus de 0

## ⚙️ Mécaniques

### Objets à attraper ✅
| Objet | Points | Catégorie |
|-------|--------|-----------|
| 📘 Cours | 10 | Études |
| 📝 Exam | 15 | Études |
| 📜 TFE | 20 | Études |
| ☕ Café | 20 | Essentiel (+12 focus) |
| 🔥 Motivation | 20 | Essentiel (+12 focus) |

### Objets à éviter ⛔
| Objet | Points | Effet |
|-------|--------|-------|
| 🐛 Bug | -15 | Reset combo |
| 🦠 Virus | -20 | Reset combo |
| 😴 Procrastination | -15 | Reset combo |

### Multiplicateurs 🎯
- **×1** : Zone normale
- **×2** : Zone précise (ligne orange)
- **×3** : Zone parfaite (ligne dorée)

## 🐙 Skins

5 variantes de la mascotte Poulpe avec des bonus différents :
- 🎓 Diplômé - Équilibré
- 💻 Studieux - Objets plus lents
- 📚 Biblio - Zone catch élargie
- 🎒 Étudiant - Plus rapide
- 🏄 Surfeur - Mode expert

## 💡 Anecdotes HE2B

Le Poulpe apparaît régulièrement pour partager des anecdotes sur la vie étudiante à la HE2B !

## 🛠️ Technologies

- React 18
- CSS-in-JS
- Images base64 intégrées (autonome)

## 📁 Structure

```
├── index.html          # Jeu jouable (ouvrir dans navigateur)
├── src/
│   └── JuggleYourStudies.jsx
├── assets/             # Images du Poulpe
├── docs/
│   └── GAMEPLAY.md     # Documentation complète
└── README.md
```

## 🚀 Déploiement GitHub Pages

1. Aller dans **Settings** → **Pages**
2. Source : **Deploy from a branch**
3. Branch : **main** / **(root)**
4. Save

Le jeu sera accessible sur `https://VOTRE-USERNAME.github.io/VOTRE-REPO/`

## 📄 License

MIT - Créé pour la HE2B

---

*HE2B • Haute École Bruxelles-Brabant* 🎓
