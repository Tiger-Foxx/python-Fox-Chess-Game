
# 🦊 Échecs 🦊

Bienvenue dans *Échecs* 🏁, un jeu d'échecs développé en Python avec la bibliothèque Pygame 🎮. Ce projet est un challenge créé par **Fox** 🦊, l'expert des défis et des renards 🐾. Préparez-vous à jouer contre un ami ou un adversaire redoutable, l'IA ! 💻⚔️


---

## 🏰 Introduction 🏰

Vous adorez les échecs mais trouvez les renards meilleurs stratèges ? 🦊 Voici votre jeu parfait ! Avec une interface graphique stylée 🎨, des mécaniques avancées et une IA qui réfléchit plus vite qu’un renard dans une basse-cour 🐔, c'est le moment de tester vos talents. 🧠✨

---

## ⭐ Fonctionnalités ⭐

- **🎨 Interface Graphique Amusante :**
  Un échiquier coloré et interactif pour jouer en beauté. Pourquoi se contenter de gris quand vous pouvez avoir toutes les couleurs de l'arc-en-ciel 🌈 ?

- **🧑‍🤝‍🧑 Mode Deux Joueurs :**
  Défiez votre ami(e) et découvrez qui est le 🦊 des échecs !

- **🤖 IA Redoutable :**
  L’IA utilise l’algorithme *Negamax* avec élagage alpha-beta pour des mouvements intelligents. Attention, elle ne fait pas d’erreurs de renard 🦊 !

- **♟️ Mécaniques Avancées :**
  Promotions, en passant, roque… Tout y est ! Et oui, même les renards suivent les règles 🧐.

- **🔄 Annuler & Réinitialiser :**
  Un mauvais coup ? Appuyez sur **Z** pour revenir en arrière ou sur **R** pour repartir de zéro ! 🕹️

- **🖌️ Choix des Plateaux :**
  Changez les couleurs pour un jeu plus fun. Chaque renard a ses préférences. 😜

- **🎶 Ambiance Sonore :**
  Des sons immersifs pour vos captures et mouvements. C’est mieux que des couinements de renards, non ? 😄

---

## 🦊 Les Règles Spéciales 🦊

### En Passant 🎯
Le coup "en passant" est comme une embuscade de renard. Voici comment ça marche :

1. Le pion adverse avance de deux cases. 🚶‍♂️
2. Hop, vous le capturez par surprise ! 💥

**Illustrations :**


---

### Promotion du Pion 🌟
Lorsque votre pion atteint la huitième rangée, transformez-le en la pièce de votre choix… sauf en renard 🦊 (les échecs n’ont pas encore ce privilège) !


---

## 🔧 Comment Jouer ?

1. **Clonez ce super projet !**
   ```bash
   git clone https://github.com/Tiger-Foxx/python-Fox-Chess-Game.git
   ```

2. **Installez les dépendances 🛠️ :**
   ```bash
   pip install pygame
   ```

3. **Lancez le jeu 🚀 :**
   ```bash
   python main.py
   ```

---

## 🕹️ Commandes

- **Sélectionnez une pièce :** Cliquez dessus, et les mouvements possibles s'afficheront. 🎯
- **Déplacez-la :** Cliquez sur une case valide, et c’est parti. 🚀
- **Raccourcis :** Annulez avec **Z**, réinitialisez avec **R**. 🔄

---

## 🤖 Configurer l'IA

- **Humain vs Humain :** 
   Dans `main.py`, définissez :  
   ```python
   SET_WHITE_AS_BOT = False
   SET_BLACK_AS_BOT = False
   ```
   
- **Humain vs IA :**
   ```python
   SET_WHITE_AS_BOT = True
   SET_BLACK_AS_BOT = False
   ```

- **Profondeur de l’IA (DEPTH) :** Modifiez dans `chessAi.py` :
   ```python
   DEPTH = 3
   ```

---

## 💌 Remerciements

Un énorme merci à la bibliothèque **Pygame** 🛠️, qui est aussi polyvalente qu’un renard 🦊 chassant de nuit 🌒. Si vous avez des idées pour améliorer ce projet, vos suggestions sont les bienvenues sur GitHub ! 🙌✨

Créé avec 🦊 et 🤍 par **Fox**. Qui a dit que les renards ne jouent pas aux échecs ? 😏
