# 🎓 JONGLE AVEC TA VIE D'ÉTUDIANT
## HE2B Edition - Document Gameplay

---

## 🎮 Concept du Jeu

Un mini-jeu mobile de type « Guitar Hero » où le joueur incarne un étudiant HE2B qui doit jongler avec les différents aspects de sa vie étudiante. Le jeu utilise la mascotte Poulpe et les couleurs officielles de la HE2B.

---

## 🎯 Objectif

Survivre **90 secondes** en attrapant les objets qui tombent dans les 4 colonnes, tout en évitant les objets malus. Plus le timing est précis, plus les points sont élevés grâce aux multiplicateurs ×2 et ×3.

---

## 🕹️ Contrôles

### Mobile / Tactile
- Taper sur les 4 boutons en bas de l'écran pour attraper les objets

### Clavier
- Touches **D - F - J - K** pour les 4 colonnes (de gauche à droite)

---

## ⚙️ Mécaniques de Jeu

### Barre de Focus
- Commence à 100% et diminue avec le temps
- Attraper des objets régénère le focus (+3 normal, +12 essentiel)
- Rater des objets fait perdre du focus (-12 à -20)
- Si le focus tombe à 0, la partie se termine

### Système de Combo
- Chaque objet attrapé augmente le combo
- Bonus de points tous les 5 combos (+20%)
- Le combo se reset si on rate un objet ou attrape un malus

### Multiplicateurs de Précision
| Zone | Position | Multiplicateur |
|------|----------|----------------|
| Normale | 75-100% | ×1 |
| Précise | 84-96% | ×2 |
| Parfaite | 88-92% | ×3 |

---

## 📦 Types d'Objets

### ✅ Objets à Attraper

| Objet | Points | Catégorie |
|-------|--------|-----------|
| 📘 Cours | 10 pts | Études |
| 📂 Projet | 10 pts | Études |
| 📝 Exam | 15 pts | Études |
| ⏰ Deadline | 15 pts | Études |
| 📜 TFE | 20 pts | Études |
| 💼 Stage | 15 pts | Études |
| ☕ Café | 20 pts | Essentiel (+12 focus) |
| 🔥 Motivation | 20 pts | Essentiel (+12 focus) |
| 💤 Sommeil | 20 pts | Essentiel (+12 focus) |
| 🎉 Soirée | 8 pts | Social |
| 🍕 Pizza | 10 pts | Random |
| 🚌 STIB | 8 pts | Random |

### ⛔ Objets Malus (À ÉVITER !)

| Objet | Points | Effet |
|-------|--------|-------|
| 🐛 Bug | -15 pts | Reset combo, -15 focus |
| 🦠 Virus | -20 pts | Reset combo, -15 focus |
| 🗑️ Spam | -10 pts | Reset combo, -15 focus |
| 😴 Procrastination | -15 pts | Reset combo, -15 focus |
| 😱 Retard | -20 pts | Reset combo, -15 focus |

---

## 🐙 Skins du Poulpe

Le joueur peut choisir parmi 5 variantes de la mascotte Poulpe :

| Skin | Bonus | Description |
|------|-------|-------------|
| 🎓 Diplômé | Stats équilibrées | Parfait pour débuter |
| 💻 Studieux | Objets -10% plus lents | Plus de temps pour réagir |
| 📚 Biblio | Zone catch +20% | Plus facile d'attraper |
| 🎒 Étudiant | Objets +10% plus rapides | Plus de challenge |
| 🏄 Surfeur | +15% vitesse globale | Mode expert |

---

## 💡 Anecdotes HE2B

Pendant la partie, le Poulpe apparaît régulièrement (toutes les **15-25 secondes**) pour partager une anecdote sur la vie étudiante à la HE2B. Ces pop-ups durent **4 secondes** et ajoutent une distraction amusante au gameplay.

**25 anecdotes uniques** couvrant :
- Les différents campus (Rue Royale, Louis Schmidt, Anderlecht, Nivelles)
- La vie étudiante (groupe WhatsApp, bibliothèque, espaces d'étude)
- Les services (aide à la réussite, service social, étudiants sportifs)
- L'ambiance pro (stages, mails, deadlines)
- Et le fameux Community Manager Poulpy !

---

## 🏆 Fin de Partie

La partie se termine soit après **90 secondes** (victoire !), soit si le focus tombe à 0. Dans les deux cas, un **message positif et motivant** est affiché.

### Écran de fin :
- Score total et combo maximum
- Badge selon le score (7 niveaux de « Poulpe Débutant » à « Diplômé avec Mention »)
- Tableau des 5 meilleurs scores de la session
- Message de motivation toujours positif

### Badges disponibles :
1. 🏅 Poulpe Débutant
2. 🎪 Tentacules du Chaos
3. 🌟 Multi-tâches Pro
4. 🦑 Survivant HE2B
5. 🎸 Poulpe Hero
6. 🏆 Légende Tentaculaire
7. 🎓 Diplômé avec Mention

---

## 🔧 Aspects Techniques

- **Framework** : React (JSX)
- **Images** : Poulpe intégré en base64 (pas de dépendances externes)
- **Couleurs HE2B** :
  - Jaune : #F5C518
  - Orange : #F7941D
  - Magenta : #D91A5B
  - Violet : #9B4F9B
  - Bleu : #0066B3
  - Turquoise : #00BFB3
  - Vert : #8DC63F
- **Responsive** : Mobile-first avec support tactile et clavier
- **Taille** : Fichier unique autonome (~130 Ko)

---

## 📁 Contenu du Package

```
he2b-game-package/
├── GAMEPLAY.md          # Ce document
├── GAMEPLAY.docx        # Version Word
├── juggle-your-studies-he2b-v2.jsx   # Code source du jeu
└── assets/
    ├── Barre_couleurs.png
    ├── POULPE_1-Diplome_.png
    ├── POULPE_3-Travail.png
    ├── POULPE_6-Bibliothe_caire.png
    ├── POULPE_10-Coeur.png
    ├── POULPE_11-e_cole.png
    └── POULPE_25_Surf.png
```

---

*HE2B • Haute École Bruxelles-Brabant*
